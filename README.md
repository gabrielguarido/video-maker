<h2 align="center">
  Video Maker - Open Source project for automated video creation
</h2>

## :smiley: Just for fun

## :question: How does it work?
1. After downloading this project into your computer, run the command `node index.js` - You'll need to install Node.js if you don't have it already.
2. By running the `index` file in your terminal, you are gonna be asked by the **`input robot`** to type a string term input, you can type any term you want. E.g: Michael Jackson
3. Related to your input, you will have to choose between 3 options: ***Who is*** - ***What is*** - ***The history of***
4. With your answers, the `index` file will call the **`text robot`** and it will:
    1. Fetch content from Wikipedia.
    2. Sanitize the content (remove useless links, references, images, etc.).
    3. Break all the content into 7 sentences.
    4. And extract key words of all the sentences, using ***IBM Watson Artificial Intelligence*** (Natural Language Understanding V1).
    5. Save all the information in a state.
5. The next one is the **`state robot`**, that will extract JSON content saved in memory by other robots, and load it to other ones.
6. The last one, so far, is the **`image robot`**, and it will:
    1. Google the information provided by the **`text robot`** and fetch an image for each sentence extracted.
    2. Then it's gonna download the images.
    3. Convert each image (resize, edit, cut useless parts, render, etc).
    4. Create a customized image for each sentence.
    5. Create a personalized Thumbnail for the YouTube video.
    
## :calendar: TO DO
[This is an ISSUE I created to organize my TO DO list](https://github.com/gabrielguarido/video-maker/issues/1)
- [ ] Finish Video Robot
- [ ] Create YouTube Robot

## :memo: License
This project is under MIT license. Check the file [LICENSE](LICENSE) for more information.
