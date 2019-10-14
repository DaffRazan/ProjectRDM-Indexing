# ProjectRDM-Indexing

## Image-Search-Indexing and Text-Indexing

1. **Text-Indexing** Using Swish-e
    - Requirements :

        a) Install Swish-e (Ubuntu's Package) 
        ![Swish-e Install](https://github.com/DaffRazan/ProjectRDM-Indexing/blob/master/pics/text-indexing/swish-e-install.png)
        b) Steps how to run **Text-Indexing**
        - Make one folder named **swish** , in folder **swish** , create one folder named **corpus**
            that contains 10 txt's files, then fill each of the files with the description.
            ![text configuration](https://github.com/DaffRazan/ProjectRDM-Indexing/blob/master/pics/text-indexing/corpus.JPG)
        - Make text-indexing configuration using syntax  ```swish-e -c main.conf```
        ![text configuration](https://github.com/DaffRazan/ProjectRDM-Indexing/blob/master/pics/text-indexing/mainconf.JPG)
        ![text configuration](https://github.com/DaffRazan/ProjectRDM-Indexing/blob/master/pics/text-indexing/conf.JPG)
        - Run text-indexing using syntax ```swish-e -w {word}```
        ![search index](https://github.com/DaffRazan/ProjectRDM-Indexing/blob/master/pics/text-indexing/search-index.JPG) 
        - Text-Indexing done.

2. **Image-Search-Indexing**
    - Place 10 pictures in ```image-search-engine/app/static/images``` (you can set any number of pictures, in this example is 10)
    - Install python-pip using syntax ```sudo apt install python3-pip```
    - Install pip requirements using syntax ```pip3 install -r requirements.txt```
    - Go to ```./app```
    - Index image using ```python3 index.py --dataset static/images --index index.csv```
    ![img indexing](https://github.com/DaffRazan/ProjectRDM-Indexing/blob/master/pics/image-indexing/indeximg.JPG)
    - Open file index.csv (image indexed) to see output
    ![Index csv](https://github.com/DaffRazan/ProjectRDM-Indexing/blob/master/pics/image-indexing/output.JPG)
    - Image-Search-Indexing done.

## **Sources:**
- Text-Indexing: Swish-e (Ubuntu's Package)
- Image-Search-Indexing: https://github.com/kudeh/image-search-engine




