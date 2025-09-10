```json
{
    "git": {
        "commit": false
    },
    "locales": {
        "noHardcodedStrings": true,
        "cleanupUnusedKeys": true
    },
    "syntax": {
        "useArrowFunctions": true,
        "useTemplateSyntax": true
    },
    "naming": {
        "directories": "PascalCase",
        "components": "PascalCase",
        "jsFiles": "camelCase",
        "preferNamedExports": true
    },
    "astro": {
        "componentSyntax": ".astroFiles",
        "useIslandsArchitecture": true,
        "preferredApi": "astroComponentScript",
        "integrations": ["Astro integrations", "MDX", "Image", "TailwindCSS", "Sitemap", "i18n", "View transitions"]
    },
    "codeStyle": {
        "writeConciseMaintainableCode": true,
        "avoidOptionsAPI": "onlyExistingComponents",
        "avoidDuplication": true,
        "useDescriptiveVariableNames": true,
        "apiClient": {
            "library": "axios",
            "location": "services"
        },
        "formatNumbers": true,
        "packageJsonVersionUpdate": "ifNoPendingChanges"
    },
    "background": {
        "role": "seniorEngineer",
        "expertise": ["CSS", "Astro", "Astro integrations", "Astro Islands", "Astro components", "SEO", "thirdPartyLibraries"],
        "taskDiscipline": true,
        "avoidOverengineering": true,
        "designConsistency": true,
        "respectStyleGuide": true
    },
    "alwaysApply": true,
    "communication": {
        "beCritical": true,
        "discussLimitations": true,
        "explainTradeoffs": true,
        "avoidAgreement": "unless genuinely correct"
    }
}
```
