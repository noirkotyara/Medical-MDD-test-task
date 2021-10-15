# Medical-MDD-test-task

Coding assignment to help candidates to show their experience in front-end development.

### Recommended stack:
*   ReactNative
*   Redux Toolkit (optional)
*   feel free to install packages you need but with a simple explanation why they

Hello! To get a feeling for your current skills regarding our front-end stack, you've been requested to do this assignment.

Feel free to be creative, so there is a simple layout:  
[figma layout](https://www.figma.com/file/YvumtX09NZltEiVaj6mTua/MDD-test-task-team-library?node-id=0%3A1)

Try getting it to work first, then make it better if you have some free time left.

### Getting started
Create a public repository on GitHub 

Send a link of your public repository on email d.maliukh@spd-ukraine.com

MDD stands for Metadata driven development,
so the main task of this coding assignment is to
create a simple form by JSON config which
resembles metadata. It will help to understand
the basic concept of MDD flow.

You have a layout on Figma and JSON file in this repository.
1. Use file Metadata.json for generating dynamically the form fields by two locales: EN, RU.
2. Create a <DynamicForm /> component that implements every type of field (Field implementation needs to be in separate components)

**For example:**
```
<EnumComponent/>
<TextComponent/>...
```

3. Do not forget about validation.
4. After the client submit the form, in console should appear a data of created record of the diagnostic report

**For example:**
```JSON
{
  "name": "Jack Doue",
  "birthDate": "1996-10-15T00:00:00.549Z",
  "bloodType":"1",
  "bodyTemperature": 36.6,
  "hasCovid": true  
}
```
5. Except for the form, you need to create a simple layout of a mobile application with a bottom menu:
* after the click on the diagnostic report button, it needs to open this form
* app needs to have a header with the logo (optional) (export from Figma) 