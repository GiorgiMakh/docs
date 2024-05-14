### Example Package.json Structure

----

```js
{
  "name": "your-package-name",       // The name of your package. It should be lowercase and url-safe.
  "version": "1.0.0",                // The current version of your package, following semantic versioning.
  "description": "A brief description of your package.",  // A short description of what your package does.
  "main": "index.js",                // The entry point of your package.
  "scripts": {                       // Scripts to run tasks such as tests, builds, etc.
    "start": "node ./index.js",
    "dev": "nodemon ./index.js",
    "build": "webpack",
    "test": "jest"
  },
  "keywords": [                      // An array of keywords to help people find your package.
    "node",
    "npm",
    "example",
    "package"
  ],
  "repository": {                    // Details about the repository where your code is hosted.
    "type": "git",
    "url": "git+https://github.com/GiorgiMakh/docs.git"
  },
  "bugs": {                          // URL to the issue tracker.
    "url": "https://github.com/GiorgiMakh/docs/issues"
  },
  "homepage": "https://github.com/GiorgiMakh/docs#readme",  // URL to the homepage of your project.
  "dependencies": {                  // List of dependencies your package needs to run.
    "module": "^4.17.1"
  },
  "devDependencies": {               // List of dependencies only needed for development and testing.
    "dev-module": "^8.3.2",
    "erroremail": "^0.0.4"
  },
  "peerDependencies": {              // List of dependencies that your package expects the host project to provide.
    "peer-module": "^17.0.1"
  },
  "optionalDependencies": {          // List of dependencies that are optional.
    "optional-module": "^2.3.2"
  },
  "bundledDependencies": [           // List of dependencies that will be bundled when publishing the package.
    "module-name"
  ],
  "engines": {                       // Specify the versions of Node.js or other engines your package is compatible with.
    "node": ">=6.0.0"
  },
  "os": [                            // Specify the operating systems your package is compatible with.
    "darwin",
    "linux"
  ],
  "cpu": [                           // Specify the CPU architectures your package is compatible with.
    "x64",
    "arm"
  ],
  "private": true,                   // If true, prevents the package from being accidentally published to the public registry.
  "publishConfig": {                 // Configuration for publishing the package.
    "registry": "https://registry.npmjs.org/"
  },
  "author": "GiorgiMakh",            // Author's name and email.
  "license": "GNU"                  // The license under which your package is distributed.
}
```
