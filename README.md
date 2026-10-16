# EdmarGasAnalyzer – wydania

Instalatory programu EdmarGasAnalyzer oraz plik `update.xml`, z którego program sprawdza dostępność nowej wersji (AutoUpdater.NET).

Najnowszą wersję pobierzesz z zakładki [Releases](https://github.com/spin-fx/EdmarGasAnalyzer-releases/releases/latest).

## Nowe wydanie
1. Podbij wersję w `EdmarGasAnalyzer.csproj` i `skrypt.iss`, zbuduj i skompiluj instalator.
2. Utwórz Release z tagiem `vX.Y.Z` i dołącz `EdmarGasAnalyzer_Setup_vX.Y.Z.exe`.
3. Dopiero potem zaktualizuj `<version>` i linki w `update.xml`.
