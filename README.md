# Sample App
_________________________
### Folder Structure
1. Controllers
    >A home for ```UIViewControllers```. I separate Scenes folder by logical modules. For example I have subfolders AccountSettings, LeftMenu, Unboarding etc. In each module I have actual folders for UIViewControllers.
2. CustomControls
    >This is folder for any ```custom elements``` I develop from scratch. I am trying to make them as modules so I can easily copy paste them to another project and use them. Here I have folders like Cells (custom prototype cells seperateed by scenes), Extensions (custom extensions) and Views (custom views).

    ```SubFolders:```
    1. Extensions
    2. CustomViews


3. Models
    >The models which are used across App keeps in this folder.
4. Resources
    >Here is two folders: ```Storyboards``` and ```Assets.xcassets``` (also here is can be another folders like Fonts, Videos etc.). I try to seperate Storyboards and Image Assets by scenes. For example I have Storyboards Unboarding, AccountSettings etc. The same for Image Assets.
5. SupportFiles
    >Contains only ```AppDelegate``` and ```Info.plist file```. Nothing special.
6. Vendors
    >Here is ```custom libraries``` or ```components``` which are not distributed over CocoaPods (or event our own frameworks which are developed as separate projects).
7. Views
    >Contains ```View Classes```. Make a sub folder Cells - contain ```UITableViewCell```, ```UICollectionViewCell``` etc.
8. Workers
    >This is our “logic” folder. Here is workers for getting data from server, from ```database```, ```caching```, ```sorting``` items etc.. Any logic with ```models works``` in this folder. Also this folder can contain subfolders like Helpers (any ```helper classes``` for example for animations, errors handling etc..), ```NetworkLayer``` (to send requests/get responses from server, authorize users and any other interactions with our server).
