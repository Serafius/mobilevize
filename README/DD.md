int itemCount = 0;
                int i = 0;
                while (catalog.getByPosition(i) != 0) {
                  itemCount += 1;
                  i++;
                }
                return Text('Total Items: $itemCount');
