# vscode-laravel
My json config on vscode at 05-2023

```
{
    "workbench.sideBar.location": "right",
    "editor.fontFamily": "Fira Code, monospace",
    "editor.fontLigatures": true,
    "terminal.integrated.fontFamily": "MesloLGS NF",
    "editor.fontWeight": "500",
    "terminal.integrated.cursorStyle": "line",
    "terminal.integrated.cursorBlinking": true,
    "terminal.integrated.cursorWidth": 2,
    "terminal.integrated.fontSize": 16,
    "terminal.integrated.lineHeight": 1.5,
    "terminal.integrated.letterSpacing": 0.5,
    "workbench.colorCustomizations": {
        "editor.background": "#222",
        "sideBar.background": "#222",
        "activityBar.background": "#222",
    },
    "editor.fontSize": 16,
    "editor.lineHeight": 35,
    "customizeUI.font.regular": "Fira Code",
    "workbench.iconTheme": "material-icon-theme",
    "customizeUI.font.monospace": "Fira Code",
    "customizeUI.titleBar": "inline",
    "customizeUI.listRowHeight": 35,
    "editor.minimap.enabled": false,
    "workbench.colorTheme": "Dracula Soft",
    "editor.inlineSuggest.enabled": true,
    "php.suggest.basic": false,
    "[php]": {
        "editor.defaultFormatter": "junstyle.php-cs-fixer"
    },
    "php-cs-fixer.onsave": false,
    "php-cs-fixer.showOutput": false,
    "php-cs-fixer.autoFixByBracket": false,
    // "php-cs-fixer.rules": "@PSR2",
    // "php-cs-fixer.config": ".php-cs-fixer.php;.php-cs-fixer.dist.php;.php_cs;.php_cs.dist",
    "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
    "[*.blade.php]": {
        "editor.defaultFormatter": "shufo.vscode-blade-formatter",
        "editor.formatOnSave": false
    },
    "yaml.schemas": {
        "file:///home/felipe/.vscode/extensions/atlassian.atlascode-3.0.3/resources/schemas/pipelines-schema.json": "bitbucket-pipelines.yml"
    },
    "atlascode.jira.enabled": true,
    "atlascode.bitbucket.enabled": true,
    "atlascode.jira.jqlList": [
        {
            "id": "a7d8a560-f340-4b7c-a417-624c681482a1",
            "enabled": true,
            "name": "My alpaclassteam Issues",
            "query": "assignee = currentUser() AND resolution = Unresolved ORDER BY lastViewed DESC",
            "siteId": "580cd01d-6b6a-4da2-8907-3c4e5abcc36c",
            "monitor": true
        },
        {
            "id": "c1214328-941b-4af3-9fe4-2a7c76f3bfe6",
            "enabled": true,
            "name": "My eduzzjira Issues",
            "query": "assignee = currentUser() AND resolution = Unresolved ORDER BY lastViewed DESC",
            "siteId": "da882a51-62c7-41bc-9cc1-574a9e9b6085",
            "monitor": true
        }
    ],
    "workbench.productIconTheme": "fluent-icons",
    "breadcrumbs.enabled": true,
    "redhat.telemetry.enabled": true,
    "files.autoSave": "onFocusChange",
    "workbench.preferredDarkColorTheme": "Dracula",
    "php-cs-fixer.lastDownload": 1683895535396,
    "git.confirmSync": false,
    "github.copilot.enable": {
        "*": true,
        "plaintext": true,
        "markdown": true,
        "scminput": false,
        "yaml": true,
        "typescriptreact": true,
        "html": true
    },
    "explorer.compactFolders": false,
    "atlascode.jira.lastCreateSiteAndProject": {
        "siteId": "580cd01d-6b6a-4da2-8907-3c4e5abcc36c",
        "projectKey": ""
    },
    "[blade]": {
        "editor.defaultFormatter": "shufo.vscode-blade-formatter"
    },
    "debug.disassemblyView.showSourceCode": false,
}
```
