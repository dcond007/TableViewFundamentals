# TableViewFundamentals
Learn how to create a table view, and populate a cell(s) dynamically with an array of data.

### Create a new Xcode project
* Set Interface to Storyboard
* Set Language to Swift
* Save project to your location of choice

### Add Objects to Main Storyboard
* Add a TableView Object
* Add a Cell Object
*   Place the cell object inside the tableview
* Add a Label object
*   Place the label inside the cell

### Create a new Cell file (Cell Class)
* Right click on project folder
* create iOS Cocoa Touch Class
* Lets name it, TableViewCell
*   The class type is UITableViewCell

### Configure a Cell and Cell Class
* Go to the Main.storyboard
* Click and highlight the table view cell
* Show the inspectors on the upper right corner
*   Identity Inspector: (license looking icon) fill in the class name, TableViewCell
*     tap enter when done
*   Attributes Inspector: (3 sliders icon) fill in the Reuse Identifier, TableViewCell
*     tap enter when done
* Add an IBOutlet to the TableViewCell class
* Hold down the ALT key and click on the TableViewCell file
*   You'll want the storyboard and TableViewCell class side by side for the next step
* Click and highlight the Label
*   While holding the CONTROL key, click and drag from the Label to the TableViewCell class
*   On the click release, set the connection to an Outlet, and name the new outlet. 

### Implement TableView Features to our View Controller
* Go to the ViewController swift file
* Implement the following classes:
*   UITableViewDelegate
*   UITableViewDataSource
* After doing this, some protocols (methods) will be need to be added
*   Click the red icon, and fix the error, two methods are now generated:
*     numberOfRowsInSection
*     cellForRowAt

### Table View Outlet and more
* We can use a handy feature called assistant editor
* Click and highlight the Main storyboard file
* Click on the paragraph looking icon, and select the assistant editor
*   the controller associated with the main storyboard is now displayed
* While holding the CONTROL key, click and drag from the table view to the ViewController swift file
*   Release the click, create and name the Outlet
* Go to the viewDidLoad() method
*   
