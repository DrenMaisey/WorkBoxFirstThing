# WorkBoxFirstThing

## Prerequisiti

- Installa Winget scaricandolo da qui: https://github.com/microsoft/winget-cli/releases

- eseguire `winget settings` da una powershell

- Incollare il seguente codice:

    `
{
    "$schema": "https://aka.ms/winget-settings.schema.json",

    // For documentation on these settings, see: https://aka.ms/winget-settings
    // "source": {
    //    "autoUpdateIntervalInMinutes": 5
    // },
    "telemetry": {
        "disable": true
    },
    "installBehavior": {
        "preferences": {
            "scope": "machine"
        }
    },
}

`

- Eseguire il file Install.ps1

## Passaggi Successivi

Installare Espanso  https://espanso.org/
