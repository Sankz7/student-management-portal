# studmgmtportalFIREBASE
CRUD application for managing student data.

steps - 

1. create marvellous database in firestore select the REALTIME database and change the permission as below.
( VIP - In rules field set the permissions as true for BOTH read and write. see eg below )
 
  "rules": {
    ".read": true,
    ".write": true
  }
}

2.  Copy below content of your created database in environment.ts file.

apiKey: “—————————————————-”,
authDomain: "fir-c9b1d.firebaseapp.com",
databaseURL: "https://fir-c9b1d.firebaseio.com",
projectId: “————————“,
storageBucket: "fir-c9b1d.appspot.com",
messagingSenderId: "387353492656" 

3. Run as it is, no other changes reqd in code. 
