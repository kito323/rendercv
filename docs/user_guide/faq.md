# Frequently Asked Questions (FAQ)

## Can I use custom fonts?

To be answered.

## Can I add a background image?

To be answered.

## How good is it in terms of parseability by ATS?

To be answered.

## How to add links?

To be answered.

## How to use Greek letters?

To be answered.

## Can I add a profile picture?

### `moderncv`

There is a built-in command in the `moderncv` package.

    \photo A command for a photo. Takes the image file name as a required argument. Takes the height of the photo and the thickness of the photo frame as optional arguments.

        \photo[<photo height >][< frame thickness >]{<photo file name >}

You can add the line into the `Preamble.j2.tex` file that is in the `moderncv` folder after initializing (run ```rendercv new "Your Name"``` command first). Keep in mind that the root directory for outputs will be the `rendercv_output` folder (when running ```rendercv render Your_Name_CV.yaml``` command). So, for example, when you have your JPG in the folder where you have your `Your_Name_CV.yaml` file then you can add the picture path so (on Windows):
```
\photo[3cm][1pt]{<<"../MyCVphoto.jpg">>}
```

See more on the [user guide for `moderncv`](https://ctan.math.washington.edu/tex-archive/macros/latex/contrib/moderncv/manual/moderncv_userguide.pdf).

### Other themes

To be answered.

## How can I switch the order of `company` and `position` in ExperienceEntry?

To be answered.
