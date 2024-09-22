# AstroJS Example

This repository contains an example of AstroJS application that is deployed on Dokploy.

1. **Adjust your Astro build config**
```js
# astro.config.ts|js|mjs
/* ... */
server: {
       port: 3000,
      host: true
  },
outDir: './astro-ssr',
```

1. **Use Git Provider in Your Application**:
   - Repository: `https://github.com/Dokploy/examples.git`
   - Branch: `main`

2. **Add Environment Variables**:
- Navigate to the "Environments" tab and add the following variable:
   ```plaintext
   NIXPACKS_START_CMD="pnpm run preview"
   ```

3. **Click on Deploy**:
   - Deploy your application by clicking the deploy button.

4. **Generate a Domain**:
    - Click on generate domain button.
    - A new domain will be generated for you.
    - You can use this domain to access your application.

    
If you need further assistance, join our [Discord server](https://discord.com/invite/2tBnJ3jDJc).
