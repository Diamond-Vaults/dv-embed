

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://diamondvaults.io">
    <img src="https://diamondvaults.io/static/media/dv-fav.11e412b4.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Diamond Vaults website integration</h3>

  <p align="center">
    Customize and embed your vault within your own website, in minutes
  </p>
</div>

## How to integrate in your website

```html
<html>
 <head>
       <title>Diamond Vault Embedded</title>

      <!-- Import Diamond Vault Integration -->
      <script
        src="https://cdn.jsdelivr.net/gh/Diamond-Vaults/dv-embed@latest/V2-build/bundle.min.js"
      ></script>

      <!-- Import Diamond Vault style -->
      <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/gh/Diamond-Vaults/dv-embed@latest/V2-build/bundle.css"
      />

  </head>
  <body>

      <!-- Put this div anywhere in your website, the vault component will be rendered inside it -->
      <div id="diamond-vaults" vaultPath="Anybodies"></div>

  </body>
</html>
```

### Integration with react.js
```tsx
export const VaultComponent: React.FC = () => {
  const vaultPath: any = { vaultPath: 'anybodies' };
  
  return <div id="diamond-vaults" {...vaultPath}></div>;
}
```
<br/>
<br/>
<br/>
<br/>

## Styling Your Vault
<img src="https://firebasestorage.googleapis.com/v0/b/nft-anybodies.appspot.com/o/Screen%20Shot%202022-05-03%20at%2014.39.50.png?alt=media&token=60932f91-ad87-4944-a6b9-e4113f2dd35a"/>


You are now able to customize the look and feel of your Vault.<br/>
To do this, you need to copy the style sheet from <a target="_blank" href="https://github.com/Diamond-Vaults/dv-embed/blob/main/build/bundle.css"> here </a>.
<br/><br/>
<b>All</b> the styling of the vault is in that file.<br/>
Copy the default styling and create a new local CSS file and overriding the design of the vault.
