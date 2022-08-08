# Troubleshooting

1. Make sure all paths in your source files are correct.
1. If you want to use npm packages in your code, set the option `baseUrl` in your `tsconfig.json` to `./node_modules` and ensure the dependencies are installed correctly.
1. If you get an error like this: `Could not find module "@parcel/transformer-sass" satisfying 2.7.0.` remove the package from the `package.json` file and run the photon build. The photon cli will automatically add the right version of all needed transformers.
