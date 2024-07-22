# Инструкция к установке перевода

*BepInEx можно установить тоже, но я хрен знает, зачем он нужен тут* </br>

[TMP_Font_AssetBundles](https://github.com/bbepis/XUnity.AutoTranslator/releases) </br>
[X Unity.AutoTranslator-ReiPatcher](https://github.com/bbepis/XUnity.AutoTranslator/releases) </br>

1. Скачайте программу X Unity.AutoTranslator-ReiPatcher;
2. Скачайте пакет шрифтов (TMP_Font_AssetBundles)
2. Перенесите файл перевода и пакет шрифтов в корень игры;
3. Запустите SetupReiPatcherAndAutoTranslator;
4. Запустите ярлык игры, созданный программой;
5. Выйдите из игры;
5. Измените config.ini в папке AutoTranslator:
    1. Language = ru;
    2. FromLanguage = ja;
    3. MaxCharactersPerTranslation = 700
    4. IgnoreWhitespaceInDialogue = False;
    5. IgnoreWhitespaceInNGUI = False;
    6. OverrideFont = arialuni_sdf_u2019 или arialuni_sdf_u2018 или на какой-либо другой шрифт в вашей OC;
    7. OverrideFontTextMeshPro = arialuni_sdf_u2019 или arialuni_sdf_u2018.
6. Перенесите папку ru в Succubus Reborn/AutoTranslator/Translation;
7. На всякий случай снова запустите ярлык игры;
8. Из папки assets можете перенести спрайты, фоны и т.п в папку UserCustomData (Не обязательно);
9. Наслаждайтесь игрой на русском языке (ярлык можно больше не запускать).