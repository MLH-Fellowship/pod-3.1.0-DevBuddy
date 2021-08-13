# Tabify


## Description
A one-stop bookmark management tool for the users. It is a chrome extension that capture all your tabs in the current window under a defined category and group to restore tabs as and when required.

## Demo


https://user-images.githubusercontent.com/45001916/129273905-8904fe43-aa74-4edf-9809-12577fd9103f.mp4


### Getting Started
To run locally on your system

`$ git clone https://github.com/MLH-Fellowship/pod-3.1.0-DevBuddy.git`

`$ cd app/`

` $ yarn install  ` 

`$ yarn build`

Navigate to `chrome://extensions` then enable the developer mode from the far right.
- Click on load unpacked on the far left

![Developer mode](./app/src/utils/images/developer_mode.png)

- locate the build folder in the project section and click add and you will get below image in your extenstion list

![Tabify](./app/src/utils/images/devBuddy.png)

Locate DevBuddy from the list of available extensions and click on it to open up the extension.

## Credit
@grace-omotoso
@tomarviii88 
@shweta3047
@netman5
@#3Tushar3099 


#### Functionalities: 

- **Add Categories/Groups**

This function allow adding of new category and group name for tabs to be capture.

![Addcategories](./app/src/utils/images/addcat.png)

- **Capture Tabs**

This feature capture the current browser window tabs with option to select category and groups based on currently available categories and group.

![capture](./app/src/utils/images/capture.png)

- **Tabs Group**

The tabs group feature when clicked popup a modal for 
- for selection of the list of saved tab urls with title
- options to either delete or restore tabs base on preference.
- option to delete entire tab group

![TabModal](./app/src/utils/images/tabmodal.png)

- **Delete to Categories/Groups**
  
To remove entire category with categories 

- **Add group to existing category**

To add group to an existing category

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

### Useful commands
Fork the project

Switch branches:
```
git checkout <branch-name>
```

Make new branch and switch to it:
```
git checkout -b <branch-name>
```

I'd recommend using the GitHub CLI for reviewing Pull Requests, making Pull Requests and making Issues.
## License
[MIT](https://choosealicense.com/licenses/mit/)
