# folders

- seguindo a documentação: https://www.reactnative.express/app/project_structure

MyApp
├── modules
│ ├── accounts
│ │ ├── components
│ │ │ ├── UserProfile.js
│ │ │ └── LoginInput.js
│ │ ├── screens
│ │ │ ├── Profile.js
│ │ │ ├── Login.js
│ │ │ └── Deactivate.js
│ │ ├── utils
│ │ │ └── formatAccountName.js
│ │ └── App.js
│ ├── growth
│ │ ├── components
│ │ ├── screens
│ │ ├── utils
│ │ └── App.js
│ ├── privacy
│ │ ├── components
│ │ ├── screens
│ │ ├── utils
│ │ └── App.js
│ └── shared
│ ├── components
│ │ ├── Avatar.js
│ │ ├── Button.js
│ │ └── List.js
│ └── utils
│ └── format.js
└── App.js

### adicional folders

MyApp
├── api
│ ├── twitter.js
│ ├── facebook.js
│ └── instagram.js
├── assets
│ ├── app-icon.png
│ └── splash-screen.png
├── hooks
│ ├── useInterval.js
│ └── useLogin.js
├── reducers
│ ├── posts.js
│ ├── users.js
│ └── tweets.js
├── theme
│ ├── colors.js
│ ├── textStyles.js
│ └── spacing.js
├── utils
│ ├── generateUuid.js
│ └── formatCurrency.js
└── ...
