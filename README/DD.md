 match /kullanici/{id} {
      allow read, write: if true;
    }
    match /arkadaslar/{id} {
      allow read: if true;
    }
