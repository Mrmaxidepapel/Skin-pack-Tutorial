# Skin-Pack Tutorial (sm64ex-coop)

- In this tutorial, I will explain step-by-step how to make a Skin-Pack for **sm64ex-coop**

- First of all, you will need to create a folder for your mod. You can choose any name you'd like

- Inside it, make a new folder called **"actors"**

- Leave the **"actors"** folder and download this file in your main folder: [main.lua](https://www.mediafire.com/file/bojweq4qgdoun9w/main.lua/file)

- Open it with any text editor you choose

- When you open the file, you should see something like this:

![Screenshot_2023-10-12-17-51-22-100-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/27abe328-51a6-4102-9a7e-6bd68894059f)

- Let's start with the **name** value. Firstly, replace "skin pack name" with the name of your choice for your mod.

- Next, we have the **incompatible** value. Whatever you put in this value will be unable to load if you have your Skin-Pack enabled. Some examples are

```incompatible:romhack``` ```incompatible:moveset```

- For the last value, we have the **description** value. This is pretty straightforward, just put the description of your Skin-Pack.

## Part 1: Adding models

- Take this image into account:

![Screenshot_2023-10-12-17-52-02-887-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/2ce23ce0-13db-45fb-8534-99b3499d3d05)


- You will need a name for your model, for example the image shows:

```E_MODEL_NAME```

- Every model variable (in this case it's E_MODEL_NAME) must have **E_** as its prefix.

- Let's use the Render96 Mario model as an example:

- We could use any of these:

```E_MARIO_R96``` / ```E_RENDER96_M```

- Note that it's recommended to use short or abbreviated names.

## Part 2: Adding the model variables to the list

![Screenshot_2023-10-12-17-52-31-362-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/cdb758a3-1e65-4ccb-a1a3-2cbe554dca09)

- Here you will have to put the previously made model variables (E_MARIO_R96, etc).



- If you want to add more variables, you can leave a space to add multiple variables, which would result in something like this:



```{nil, E_MARIO_R96, E_OTHER_MODEL}```



## Part 3: Adding the model names to the list



- Now that we have added the model variables, we're on the last required step!



- Let's go down to this section:

![Screenshot_2023-10-12-17-52-52-728-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/40103162-74c8-4120-93c4-3ad55fb8b5a7)

- You will have to put the names for the models you chose.

- Remember to write the names like this: {'Model 1', 'Model 2'}

- Here's an example with the Render96 model from earlier:

```{nil, E_RENDER96_M, E_OTHER_MODEL, E_OTHER_MODEL_2```

```{'Default', 'Render96 Mario', 'Other Model 1', 'Other Model 2'}```

**WARNING**:

- Remember to make the order of the variables and names match.

- This is an example of what it would look like if the names and variables didn't match.

```{E_RENDER96_M, E_OTHER_MODEL, E_OTHER_MODEL_2}```

```{'Other Model 2', 'Render96 Mario', 'Other Model'}```

## Changing sounds (optional)

(Note that this doesn't mean adding sounds of your own. This is for changing the sounds to other ones already in the game.)

- This one is simple:

![Screenshot_2023-10-12-17-53-35-946-edit_com ace ex file manager](https://github.com/Mrmaxidepapel/Skin-pack-Tutorial/assets/143361819/b81c6a4c-2a89-41f8-803e-24b8e558138e)

- Change the sounds to the ones you prefer.

## Important information

- 1) All models must have the .bin file extension, do not add any textures or .c files.

- 2) Remember you cannot put spaces in your model variables, you can use this instead: **_**

- 3) The main.lua file used is a version without credits at the top, maybe soon I will release the version with credits...

## Thank you for reading this, if you find any problems just use the Issues tab.
