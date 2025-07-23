# prettier-config

My prettier config for easy reuse across various projects.

## How To Use

1. Install Prettier and this package.
   ```bash
   pnpm add -DE prettier @voidrender/prettier-config
   ```
2. In your `package.json`, add the following:

   ```json
   {
     "prettier": "@voidrender/prettier-config"
   }
   ```

Or you can extend the configuration in your configuration file to override specific settings.

## Suggested .prettierignore

```
package.json
node_modules
```
