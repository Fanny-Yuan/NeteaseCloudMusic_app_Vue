# NeteaseCloudMusic_app_Vue
A simple copy of Netease Cloud Music app based on Vue.

## Install
This work is based on Vue, you can set up a Vue project, and replace files in src folder with all files provided in this repository.

In order to visit music data, Netease Cloud Music API is used in this project. Before running the front-end code, you should build a netease server at first. You can find more details on https://github.com/Binaryify/NeteaseCloudMusicApi. Follow the instructions to build the server.

## Features
### Main page
![alt text](https://github.com/Fanny-Yuan/NeteaseCloudMusic_app_Vue/blob/master/imgs/main%20page.JPG)
1. Show music information got from the api based on Axios.
2. Use Vant components to realize swipe. You can find instructions on vant from: https://youzan.github.io/vant/#/zh-CN

### Music List
![alt text](https://github.com/Fanny-Yuan/NeteaseCloudMusic_app_Vue/blob/master/imgs/music%20list.JPG)
1. Use router to redirect the interface and transfer parameters.
2. Use Vuex to manage states.
3. Use watch to realize music playing.

### Song page
![alt text](https://github.com/Fanny-Yuan/NeteaseCloudMusic_app_Vue/blob/master/imgs/music%20play.JPG)
1. Use Vue3 Marquee to realize head dynamic features.
2. Realize animation effect of the disk and needle when playing and stopping the song.

![alt text](https://github.com/Fanny-Yuan/NeteaseCloudMusic_app_Vue/blob/master/imgs/lyrics.JPG)

3. Show lyrics when clicking the disk.
4. Use watch and timer to highlight current lyric.
5. Realize the progress bar.
6. Switch from one song to the next or the last.

