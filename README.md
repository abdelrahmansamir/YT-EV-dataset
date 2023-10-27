# YT-EV-dataset

**Y**ou**T**ube's **E**ducational **V**ideos dataset

the dataset contains more than 700 transcripts of YouTube educational videos segmented by the timestamps provided by the video author.

The dataset can be used in video segmentation tasks.

The dataset is available via this link [https://drive.google.com/drive/folders/12NEwqBVa5HgMAqFPDCks0B6Ogb5tU-74](download the dataset)

*note*: the file name is the YouTube video id.

## code

The whole code is available in this file

```
collectYoutubeDataset.ipynb
```

you can extend this dataset by adding a new list of search keywords in the file `coursesNames.txt`

or add some playlist IDs in the file `playlistIds.txt` 

### run the code

use this function to extend the dataset using search keywords

```
# used to get the transcript segments by search 
getSegmentsBySearch(0)
```

or use this function to get new transcripts by playlistIds

```
# used to get the transcript segments from the playlist 
getSegmentsFromPlaylists(0,2)
```
