#### Baka-Merged
  * Why im make this?. because im lazy to write every time if i'am merged. so i decided to make script like that make its simple to merged drivers kernel and everyone who want to use will know too.

#### how to use?
  * wget file
   ```
   wget https://raw.githubusercontent.com/Baka-Project/Baka-Merged/baka/baka-merged
   ```
  * Open file baka-merged
  * edit account and username github
  * Edit tag you need to merged for example LA.UM xxxxxxxxxxxxxx
  * Edit type what you want to use
    ```
    merged-initial # as merged qcacld - fw api - qcmn
    update-drivers/techpack # as update driver qcacld - fw api - qcm | techpack
    techpack-initial/data/audio/video/camera/display # as merged techpack audio and data
    ```
  * Use CI/CD or localy and run with
     ```
     bash baka-merged or ./baka-merged
     ```
  * Note!!

    * uncomment like this if you want use ci/cd for merged and push simple

      * `# REPOSITORY` --> REPOSITORY

      * `# GITHUB_TOKEN` --> GITHUB_TOKEN

      * `# git push` --> git push
