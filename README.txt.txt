1.Samuel Pearson 10711339
2.Python
3. 
1st - importing stuff
2nd - reading in the images from google cloab - they are then transformed into an array
3rd - the array becomes a data frame with person, perspective, emotions, eyes, and pixels
4th - An images array is created from the dataframe pixels (a sample image is also printed here "plt.imshow(train_X[4,:,:], cmap='gray')")
change "4" to wtv number you want to see various images
The labels for the model are also set up here
5th - test_train_split set up
6th - normalizing the array
7th - neural net with lots of layers (online implementation from https://medium.com/analytics-vidhya/facial-emotion-recognition-fer-using-keras-763df7946a64)
used for understanding how to code neural net
8th - image data generator
9th - final model set up
10th - model run
11th - results plotting

4.
You will need to change the location of the file in lines 35 and 43 to wherever you store the images
You can also change the 4 in line 88 to display a different image
It should compile and run in python... I did it in google colab, and have never used python until now... so 
I can't say 100% sure, but I think it will work
Alright I have a 15 page paper due in 3 hours, wish me luck, it's been a hell of a semester

Thanks for reading, it's been fun!