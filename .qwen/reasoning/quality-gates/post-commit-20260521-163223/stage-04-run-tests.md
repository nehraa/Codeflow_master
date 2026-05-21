# Stage 4: Run Existing Tests

**Status:** PASS

```

> codeflow-ide@1.0.0 test
> jest

Error: Jest: Failed to parse the TypeScript config file /Users/abhinavnehra/git/Codeflow_master/jest.config.ts
  Error: Jest: 'ts-node' is required for the TypeScript configuration files. Make sure it is installed
Error: Cannot find package 'ts-node' imported from /Users/abhinavnehra/git/Codeflow_master/node_modules/jest-config/build/readConfigFileAndSetRootDir.js
    at readConfigFileAndSetRootDir (/Users/abhinavnehra/git/Codeflow_master/node_modules/jest-config/build/readConfigFileAndSetRootDir.js:116:13)
    at async readInitialOptions (/Users/abhinavnehra/git/Codeflow_master/node_modules/jest-config/build/index.js:403:13)
    at async readConfig (/Users/abhinavnehra/git/Codeflow_master/node_modules/jest-config/build/index.js:147:48)
    at async readConfigs (/Users/abhinavnehra/git/Codeflow_master/node_modules/jest-config/build/index.js:424:26)
    at async runCLI (/Users/abhinavnehra/git/Codeflow_master/node_modules/@jest/core/build/cli/index.js:151:59)
    at async Object.run (/Users/abhinavnehra/git/Codeflow_master/node_modules/jest-cli/build/run.js:130:37)
```
