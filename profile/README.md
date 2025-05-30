## [start here](https://github.com/Technische-Informatik-Ausarbeitungen/.root.git)

[Don't know what master to choose?](../MasterPrograms.md)

## `git lfs`

Damit Files $>100 \ \text{MB}$ auf GitHub hochgeladen werden können, muss *git lfs* aktiviert werden.
Das Setup kann [online](https://git-lfs.com/) einfach runtergeladen werden. Die Einstellungen für das Repository müssen nicht mehr gemacht werden.

Nach der Installation muss dies *einmalig* für den User aktiviert wrden:

```shell
git lfs install
```

mit

```shell
git lfs track "*.pdf"
```

können Dateitypen als *Large File Storage* deklariert werden, dies ist jedoch nur für Binärfiles zu empfehlen.

