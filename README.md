# StereoKit Rubiks 2022

## Hva trenger jeg for å starte?

Du trenger en Windows eller Linux maskin, men Windows er klart foretrukket. Mac er ikke støttet, da det enn så lenge ikke finnes noe VR for Mac.

I eksempelet bruker vi i tillegg dette:

- `dotnet 6` (Last ned her: <https://dotnet.microsoft.com/en-us/download/dotnet/6.0> )
- `Visual Studio Code` (<https://code.visualstudio.com>)
  - Installer C# extension (Søk etter `C#` eller `ms-dotnettools.csharp` i plugins)

Last ned og sett opp dette. Mange har kanskje dette installert i fra før av om dere har erfaring med dotnet utvikling. Det er også mulig å bruke alternativer til VS Code, feks Visual Studio eller Rider.

Dersom du har et VR headset som for eksempel Oculus Quest, kan du koble dette til PCen din ved hjelp av "Last ned Quest appen til PC" på denne lenken: <https://www.oculus.com/setup/>, og så koble det inn med USB kabelen. Du må kanskje sette opp utvikler modus og litt ekstra, men det skal være helt greit å google seg frem til.

Om du ikke har noe VR headset enda kan du fortsatt teste appen din på flatskjem, så følg med oss videre.

## En enkel start

For å sette opp ditt første stereokit prosjekt kan du kjøre disse kommandoene i en terminal. Om du ikke er helt komfortabel med dette har vi lagt ved et prosjekt der dette allerede er gjort.

```pwsh
mkdir "StereoKitHelloWorld"
cd "StereoKitHelloWorld"
dotnet new console
dotnet add package StereoKit --prerelease
```

Du kan nå åpne mappen StereoKitHelloWorld i Visual Studio Code (om du fortsatt har oppe terminalen kan du skrive `code .` som vil åpne VS Code i mappen)

