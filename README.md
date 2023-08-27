# YT-EV-dataset

**Y**ou**T**ube's **E**ducational **V**ideos dataset

the dataset contains on more than 700 transcript of YouTube educational videos segmented by the timestamps provied by the video author.

The dataset can be used in video segmentation tasks.

The dataset is available via this link [https://drive.google.com/drive/folders/1FsCvusv895KlkNXf6MYjzbG1bonciJ65?usp=sharing](download the dataset)

*note*: the file name is the youtube video id.

## code

The whole code is available in this file

```
collectYoutubeDataset.ipynb
```

you can extend this dataset by adding a new list of seach keywords in file `coursesNames.txt`

or add some playlist ids in file `playlistIds.txt` 

### run the code

use this funtion to extend the dataset using search keywords

```
# used to get the trascript segments by seach 
getSegmentsBySearch(0)
```

or use this funtion to get new transcripts by playlistIds

```
# used to get the trascript segments from playlist 
getSegmentsFromPlaylists(0,2)
```
