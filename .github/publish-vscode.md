# Publicar extensión de VS Code
Primero, necesitas una cuenta en Azure DevOps (anteriormente Visual Studio Team Services). Puedes crearla en: https://dev.azure.com/
Una vez que tengas tu cuenta, necesitas obtener un Personal Access Token (PAT):

-   Ve a https://dev.azure.com/{tu-organización}/usersSettings/tokens
-   Crea un nuevo token con los permisos de "Marketplace (publish)"

Instala vsce globalmente:

```bash
pnpm install @vscode/vsce
```

Inicia sesión con tu token:

```bash
pnpm vsce login <publisher-name>
pnpm run dist
```

O directamente:

```bash
pnpm vsce publish
```
