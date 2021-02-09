# Kajabi UXD Candidate Code Challenge

Welcome! We're excited you're interested in joining the Kajabi UX Developer (UXD) team! This code challenge gives you an opportunity to show us where you are in relation to crucial skills for day to day work at Kajabi.

## Your challenge, should you choose to accept it...

The overall goal of this challenge is to create a prototype component using HTML and CSS based on a provided design mockup. **We would ideally like for you to return this challenge within one week.**

Here's the process:

1. Review [this Figma mockup](https://www.figma.com/file/XfwsvOqsrt4nLTUCHdcBP7/Challenge-Latest?node-id=0%3A1) for a fictitious new component that is similar to something you might build on the job with us. _Note:_ If you're new to Figma, that's ok! See the section below, "Regarding Figma."
1. Use the starter file set provided in this repo within the `src/` folder to recreate this component. 

    As you plan your approach consider the following:
    
    - Match the component mockup as closely as you can. We are interested in seeing how you would build this using contemporary HTML and CSS techniques.
    - You are welcome to use plain HTML and CSS in the provided `src/index.html` and `src/styles.css`. However, if you're familiar with Sass you can also use the minimal build process we've set up here. Either way, see "Regarding local development" below for some tips regarding the setup we've provided to help you get going on the task.
    - No interactivity is required or expected here. While we complete our work in a Rails and React environment on the job we do not expect you to showcase skills in these tools for this challenge.
    - We welcome (but do not require) additional considerations of responsive adjustments. Matching the mockup provided should be your first priority, but feel free to consider creative adjustments for smaller screens.
    - We don't expect you to use the newest, most "bleeding edge" features. Just show us what you know, where you are now. Don't overthink it ;). Simple, effective solutions are ideal.
    - While we hope to see the mockup built as shown, there may be aspects of the component that present some questions to you and affect your approach. Go ahead with your best guess or assumption but feel free to articulate your thought process in the provided `NOTES.md`.
    - Along these lines, please provide any additional explanation or background on your solution in the `NOTES.md` file that you think would be helpful to those who review your solution.

1. Set up a Github repo containing your finished work on the `main` branch. Then **share your repo's URL with your primary contact at Kajabi.** They will pass it on to reviewers on the UXD team.

If you have any questions or concerns about the task or anything related to completing and submitting the project please let your primary contact at Kajabi know.

## Regarding Figma

If you're new to [Figma](https://www.figma.com/) you will find it has a lot in common with other design software such as [Adobe XD](https://www.figma.com/figma-vs-adobe-xd/), [Sketch](https://www.figma.com/figma-vs-sketch/), and Axure. It can run in a browser or as a desktop application and is therefore also available for Mac and PC.

At Kajabi our Design team uses Figma for a variety of tasks from creating wireframes to high-fidelity mockups. When a component or screen design is finished they hand it off to UX Developers. We then build the HTML and CSS code needed in order to implement the component or screen in our application.

You can [create a free account with Figma](https://www.figma.com/) in order to access the mockup for this challenge and browse it in a more detailed fashion.

If for any reason you have trouble accessing the mockup above or creating an account with Figma, you can instead base your work on this screen shot of the mockup:

![Screen mockup](mockup.png)

## Regarding local development

You are welcome to work with plain HTML and CSS in the provided `src/index.html` and `src/styles.css` file. We have also provided a minimal live reload/build process you are also welcome to use.

First install necessary packages with the NPM install command:

```
npm install
```

To work using a minimal development build process with Sass run:

```
npm start
```

Or if you'd prefer to write plain CSS you can add it in `styles.css` and at least fire up a reloading browser with:

```
npm run sync
```

The `start` and `sync` commands both fire up a browser window that will automatically reload when you save files inside the `src` folder. If you opt to use Sass and use the `start` command your Sass included in `styles.scss` will compile into `styles.css`.

## Final remarks

We hope you enjoy completing the challenge and we certainly look forward to seeing your submission. Good luck!

Sincerely,\
Kajabi UXD Team
