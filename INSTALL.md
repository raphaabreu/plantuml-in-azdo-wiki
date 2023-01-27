Install on windows:

1. Install scoop

   ```powershell
   Set-ExecutionPolicy RemoteSigned -Scope CurrentUser # Optional: Needed to run a remote script the first time
   irm get.scoop.sh | iex
   ```

1. Install structurizr-cli

   ```powershell
   scoop bucket add extras
   scoop install structurizr-cli
   ```

1. Install plantuml and graphviz

   ```powershell
   scoop install plantuml
   scoop install graphviz
   ```

1. Restart VSCode

1. Run `npm run watch`
