---
difficulty: 1
chapter: "Chapter 1: Vue.js Essentials"
training: true
tags: vue
---

# Make Interactive Ratings


# Challenge Description
In this challenge, let’s continue development on the Movie Rating App. Instead of the rating stars being for display purposes only, 
let’s transform them into clickable buttons that allow end users to provide their own rating.

## Requirements
- Remove the display-only stars that we coded in the last challenge
- Create buttons for each rating from 1 to 5 and display a star inside.
- Color the stars based on the movie rating. For example, if the movie rating is 3, color 3 stars yellow and 2 gray.
- Allow the end user to click on any of the 5 buttons to update the movie rating accordingly.
- Disable the button for the currently selected rating to prevent the user from giving the same rating twice.

## Other Considerations

- If you see the `data-test` attribute anywhere in the boilerplate don't remove it.
- TailwindCSS is preinstalled with the default config. It might be helpful for you, if you want to have some styles. (Not obligatory)


---

# Improve the Rating UX

# Challenge Description

In this challenge, let’s present each movie’s ratings prominently with a big star and the rating number in the top right hand corner of the movie poster.

## Requirements

- Display each movie rating number within a large yellow `StarIcon` in the top right hand corner of the movie posters
- For movies with no rating, show a dash (-) instead of the number and color the `StarIcon` gray

> 💡 HINT: You can use the tailwind classes `text-yellow-500` and `text-gray-500` to help color the star
>
> 💡 HINT: You can give the movie rating a null value in movies.json to test the proper display of a movie with no rating

## Other Considerations

- If you see the `data-test` attribute anywhere in the boilerplate don't remove it.
- TailwindCSS is preinstalled with the default config. It might be helpful for you, if you want to have some styles. (Not obligatory)

### Example of Finished App

This is an example of what the functionality should look like for the completed exercise. If you’d like to mimic this style, feel free to do so, but it is not required.

> ![Finished app in this challenge](https://i.imgur.com/WBcL8yj.png)


## Example of Finished App

This is an example of what the functionality should look like for the completed exercise. If you’d like to mimic this style, feel free to do so, but it is not required.

![Finished app in this challenge](https://i.imgur.com/VjiCITj.gif)
#
