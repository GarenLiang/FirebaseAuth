# FirebaseAuth

* React Native Auth Client Side Parts :bowtie: :sunny: :heart:
* add componentDidMount() in the main.js with firebase connect

```javascript
  componentDidMount() {
        const config = {
        apiKey: "",
        authDomain: "",
        databaseURL: "",
        projectId: "",
        storageBucket: "",
        messagingSenderId: ""
      };
    firebase.initializeApp(config);
    }

 ```
