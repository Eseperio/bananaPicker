Banana Picker
=============
HTML5 & JS Responsive file manager and icons list jQuery Plugin

#Top features#
Custom callback.
Multiple selection mode
Icons font finder


To use add banana.css and banana.js to your document. 
##Usage##
$(element).banana(options)

Options available:
```
            url: "",                    //Url to retrieve data
            urlUpload: "",              //Url to upload script
            folder: "",                 //Default folder to open
            target: "",                 //(id|class|jQuery|function) Where to set selected value
            tagTarget: "",              //Images only, target for automated SRC tag created with the url of image selected
            tagTargetClass: "",         //Additional classes for the Src tag created
            thumbsFolder: "thumbs/",    //Thumbs folder
            resetFolderOnStart: true,   //If false, the last folder opened will remain opened
            allowDelete: true,          //Enable or disable delete buttons
            confirmDeletion: false,     //If true a confirmation dialog will appear before delete file
            multipleUpload: true,       //Allow multiple selection when uploading a file
            allowUpload: true,          //Show or hide upload box.
            allowFolderCreate: true,    //Show or hide create folder icon and form
            multiple: false,            //Wether use multiple selection or single,
            selectedColor: false,       //Color to use for selected elements.
            preview: true,              //Enable preview screen when file is selected
            fileTypes: false,           //View only certain datatypes. Use an array with extensions (For images use ["image"]). Remember that this will only filter view, not load. fileTypes is sended to server too, so filter in server also.
            preloadPreview: true,       // Preload the next and previous image to make transition smooth
            hideEmptyFolders: false,    // Only for tree view. Hides all folders that haven´t files (Or have not any of extensions filtered),
            imageLabels: true,          // Show a label with filename near the thumb. Only on hover
            
            token: "",                  // If your app needs to send a token set here,
            tokenName: "token",         // Name to use when the token is sended
          
            iconsMode: false,            // Enable icon mode. This disables other configuration except [multiple, preview].
            iconsData: [],               // JSON file with icons info. Array or url to JSON
            iconsPrefix: "fa fa-",       // Prefix of the fontFamily. Defaults to FontAwesome by Dave Gandy
````
