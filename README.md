# Dbank
### Decentralised Banking Made Easy 
<h1>UI : </h1>

![ss1](https://user-images.githubusercontent.com/77736746/212484993-b6a232c7-0c8a-4b3b-b533-4a236f66c064.jpg)

<h1>Features : </h1>
<ul>
    <li>Frontend : Three.js (Spline), HTML, CSS, JS
    </li>
    <li>Backend : Motoko
    </li>
    <li>Built on the <b> Internet Computer Blockchain</b>
    </li>
    <li>Functionalities :
        <ul>
        <li>Addition and Withdrawal of amount</li>
        <li>Check Balance</li>
        </ul>
    </li>
    <li>Animated Background - Hover mouse around and over the icons</li>
</ul>
<h1>Deployment</h1>
<p>  
To start working on the project right away, clone this repo and try the following commands:

```bash
cd dbank/
dfx help
dfx config --help
```

<h3> Running the project locally</h3>

To test project locally, use the following commands:

```bash
# Starts the replica, running in the background
dfx start --background

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```

Once the job completes, the application will be available at `http://localhost:8000?canisterId={asset_canister_id}`.

Additionally, to make frontend changes, start a development server with

```bash
npm start
```

Which will start a server at `http://localhost:8080`, proxying API requests to the replica at port 8000.
</p>
    
<h1> Video Demo : </h1>

https://user-images.githubusercontent.com/77736746/212485665-fc66ce4e-a799-4053-b792-4ccbb2131aec.mp4



<!--
Welcome to your new dbank project and to the internet computer development community. By default, creating a new project adds this README and some template files to your project directory. You can edit these template files to customize your project and to include your own code to speed up the development cycle.

To get started, you might want to explore the project directory structure and the default configuration file. Working with this project in your development environment will not affect any production deployment or identity tokens.

To learn more before you start working with dbank, see the following documentation available online:

- [Quick Start](https://sdk.dfinity.org/docs/quickstart/quickstart-intro.html)
- [SDK Developer Tools](https://sdk.dfinity.org/docs/developers-guide/sdk-guide.html)
- [Motoko Programming Language Guide](https://sdk.dfinity.org/docs/language-guide/motoko.html)
- [Motoko Language Quick Reference](https://sdk.dfinity.org/docs/language-guide/language-manual.html)
- [JavaScript API Reference](https://erxue-5aaaa-aaaab-qaagq-cai.raw.ic0.app)

If you want to start working on your project right away, you might want to try the following commands:

```bash
cd dbank/
dfx help
dfx config --help
```

## Running the project locally

If you want to test your project locally, you can use the following commands:

```bash
# Starts the replica, running in the background
dfx start --background

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```

Once the job completes, your application will be available at `http://localhost:8000?canisterId={asset_canister_id}`.

Additionally, if you are making frontend changes, you can start a development server with

```bash
npm start
```

Which will start a server at `http://localhost:8080`, proxying API requests to the replica at port 8000.

### Note on frontend environment variables

If you are hosting frontend code somewhere without using DFX, you may need to make one of the following adjustments to ensure your project does not fetch the root key in production:

- set`NODE_ENV` to `production` if you are using Webpack
- use your own preferred method to replace `process.env.NODE_ENV` in the autogenerated declarations
- Write your own `createActor` constructor

-->
