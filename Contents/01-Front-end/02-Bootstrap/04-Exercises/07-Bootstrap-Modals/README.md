## Background & Objectives

 A modal window is a graphical control element subordinate to an application's main window. It creates a mode that disables the main window but keeps it visible, with the modal window as a child window in front of it. Users must interact with the modal window before they can return to the parent application.

 Modals are a basic component for interfaces design. You can find <a href="https://getbootstrap.com/docs/4.0/components/modal/">here bootstrap's documentation about modals.</a>

 For this work, you will create one of the most common type of modals: the confirmation modal.

## Specs

You are working on a social network-like website. Users have the option to view and delete videos. For this exercise, you have an `index.html` file with a basic structure already done.

On this structure, you have added a HTML tag to visualize a video, and you have added a red button to allow the user to delete that video. Deleting is a very dangerous thing to do, as it can not be undone. Therefore, you better be really sure that the user knows what he is doing.

Your mission: add a modal that will open when the user clicks on the `delete` button. The modal will ask the user to confirm the action, and it will also have the option to `cancel` and close the modal.

For the moment you don't have to make the `confirm` button to do anything, as you still don't know javascript. Just put a normal button from bootstrap there.

## Tips

- Take a moment to review the existing code on the `index.html`. We have not seen never a HTML `video` tag, but this is an interesting opportunity for you to learn how it works looking at this example.
