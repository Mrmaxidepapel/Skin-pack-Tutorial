# Skin-pack-Tutorial (Ex-coop And PC-PORT)

- This Tutorial will explain step by step how to make a Skin-pack for **sm64ex-coop** or **SM64PC-Port**.

- All this text includes a file with the [main.lua](https://www.mediafire.com/file/bojweq4qgdoun9w/main.lua/file) file of a skin pack.

- First of all an **important notice**:

you will need to create a new folder called **Actors**.

- Now that you have the folder you will enter to the [main.lua](https://www.mediafire.com/file/bojweq4qgdoun9w/main.lua/file) file and you will edit this:

![Screenshot_2023-10-12-17-51-22-100-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/aea8e42a-4204-4bab-bd89-639e05369289)

- The name value will be used for the **name**.

- The incompatible version will be used for point out what will not be compatible, example:

```-- incompatible: romhack```
- The Description value will be used for as it says, the description of your skin pack.

- Now that you know that, let's move on to:

## Add Models -- indicators

- Take this image into account:

![Screenshot_2023-10-12-17-52-02-887-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/2d6c23ec-e14f-40f0-9237-b5dad097aacd)

- The value that starts with **E_** It will be our indicator for the model.

- Every indicator must start with **E_**.

- You will need a name to indicate it, for example the image shows the name of:

```E_MODEL_NAME```

- Let's take Mario Render96 as an example:

```E_MARIO_R96``` / ```E_RENDER96_M```

- It is best to use short or abbreviated names.

- Now that you know, let's move on to:

## Add Models -- Add to the list 1

- Now with everything ready, lets move to this value:

![Screenshot_2023-10-12-17-52-31-362-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/96d244d8-514d-481e-9a30-a1e0ebf53c4c)

- Here they will be added to the list, to add them you will use the indicators previously made.

- If you want to add more you will leave a space to add another, something like this would be:

```{E_MARIO_R96, E_OTHER_MODEL}```

- Now with all this done, let's move on to:

## Add Models -- Add to the list 2

- We have everything done, we need the last step, **add the names for the indicators/models**, When setting the indicator, we will have to indicate a name, we will go down to this value:

![Screenshot_2023-10-12-17-52-52-728-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/ed747994-e755-48fd-a4c1-02ebd39c2314)


- Now with this we will put the names in the same order of the indicator also added in **Add Models -- Add to the list 1**.

- For example:

```{E_RENDER96_M, E_OTHER_MODEL, E_OTHER_MODEL_2```

- oh right, when you name the indicators they will be marked with a **('text')**

```{'Render96 Mario', 'Other Model 1', 'Other Model 2'}```

**WARNING**:

- The wrong way would be this:

```{E_RENDER96_M, E_OTHER_MODEL, E_OTHER_MODEL_2}```

```{'Other Model 2', 'Render96 Mario', 'Other Model'}```

**END OF WARNING**

- Finally:

## Custom Sounds

- This one is simple:

![Screenshot_2023-10-12-17-53-35-946-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/f7c7ece1-4f46-4228-a1ed-b28939c20d56)

- The first 2 and 4 values ​​will be used for selection sounds, the 3rd sound will be used for finish selecting

- We are done with:

## Some stupid rules

- 1) All models must be in .bin, without textures or .c files

- 2) To put spaces in the indicators, a **(_)** will be used

- 3) The version shown is a version without credits at the top, maybe soon I will release the version with credits...

## Now...

- With all this information you are ready to make your own skin packs step by step for sm64ex-coop or PC-Port!!!
