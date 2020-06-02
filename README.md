# youtube-music

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alex2844/youtube-music/blob/master/ymusic.ipynb 'Open In Colab')

## Скачивание файлов, торрентов и магнитов в Google Drive

#### Справка
```
:$ ymusic --help
-h, --help             Print help
-v, --version          Print program version
--auth                 Authorization
-a, --all              Download all liked songs
-o, --one ID           Download one song
-s, --sync             Sync with android phone
```

#### Установка на локальную машину (Например ubuntu)
```bash
curl -sL https://raw.githubusercontent.com/alex2844/youtube-music/master/install.sh | sudo -E bash -
```

#### Запуск в Colab (Например если не хотите ставить python)
* Нажмите на значок с надписью 'Открыть в Colab'
* Запустите (Runtime -> Run all)
После завершения загрузки, загруженные файлы будут находиться на вашем google диске в папке с именем 'ymusic'

#### TODO
* Добавить видео инструкции
