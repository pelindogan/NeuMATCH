# A Neural Multi-sequence Alignment TeCHnique (NeuMATCH)
---------------------------------------------------------------------------
YouTube Movie Summaries (YMS) Dataset Release
---------------------------------------------------------------------------

We are making the dataset YMS (YouTube Movie Summaries) with the annotations and the corresponding video URLs available for research
purposes. If you would like to use the dataset for any other purposes please contact the authors.

### Introduction
This dataset contains 94 movie summary videos from various YouTube channels. You can find the explanation of each file below:

`YMS/movie_list.txt` - the list of video titles with the corresponding numbering

`YMS/url_list.txt` - the list of video URLs with the corresponding numbering

`YMS/annotations_sentences.txt` - annotation of the narrator sentences

`YMS/annotations_phrases.txt` - annotation of the narrator phrases (if available)

`YMS/clip_segmentation.txt` - list of over-segmented clips that we used in our experiments

In the annotation files, the video parts with "UNMATCHED" annotation represent the clips that do not have any corresponding narrator phrase/sentence. If a video part has an annotation sentence/phrase which starts with "UNMATCHED:", that clip and the phrase/sentence do not have correspondances in the other medium. 

### Citing NeuMATCH

NeuMATCH was initially described in [arXiv](https://arxiv.org/abs/1803.00057) and was subsequently published in CVPR 2018.

If you find NeuMATCH useful in your research, or if you use the YMS dataset, please consider citing:

    @inproceedings{Dogan18neumatch,
        author    = {Pelin Dogan and Boyang Li and Leonid Sigal and Markus Gross},
        title     = {A Neural Multi-sequence Alignment TeCHnique (NeuMATCH)},
        booktitle = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
        year      = {2018}
    }

### Contact
You can reach us via `pelindogan08@gmail.com`

If you have any questions related to the dataset please let us know.
