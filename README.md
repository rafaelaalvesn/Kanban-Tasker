# Kanban Board UWP

This Universal Windows Platform (UWP) application uses a Kanban Board to create a workflow for a specific task or multiple tasks. 

My initial purpose of this application was to track a single programming progject and keep track of where I'm at on certain tasks 
for that project.  

Implemented with a Sqlite database to store the tasks and uses CRUD operations against the data. You can view the .db file generated by the project with https://sqlitebrowser.org/

![Image of Program](https://github.com/hjohnson12/KanbanBoardUWP/tree/master/KanbanBoardUWP/Images/KanbanBoard.PNG)

## Getting Started

The program requires a license from Syncfusion since the Kanban Control is a control used by them, but they provide a free community license here: https://www.syncfusion.com/products/communitylicense

Essentially, generate a key for the UWP controls and head to App.xaml.cs and add your key into the string "YOUR_API_KEY". 

### Prerequisites

Minimum version: Windows 10, Version 1809

Target Version: Windows 10, Version 1903

Nuget Packages Installed:

Microsoft Sqlite should be installed on your system by default. So, the nuget package "Microsoft.Data.Sqlite" or "Microsoft.Data.Sqlite.Core" will
work. SQLitePCLRaw.bundle_winsqlite3. (Tutorial on these installations can be found on microsoft docs here: https://docs.microsoft.com/en-us/windows/uwp/data-access/sqlite-databases)

Syncfusion.SfKanban.UWP Nuget Package should be installed.

## Built With

* [Universal Windows Platform](https://developer.microsoft.com/en-us/windows/apps) - The desktop framework used
* [Syncfusion for UWP Kanban Board](https://www.syncfusion.com/uwp-ui-controls/kanban-board) - UI Kanban Board used
* [Sqlite - Started with tutorial by Microsoft](https://docs.microsoft.com/en-us/windows/uwp/data-access/sqlite-databases) - Database Framework 

## Contributing

[Coming Soon]

## Authors

* **Hunter** - *Initial work* - [hjohnson012](https://github.com/hjohnson012)

See also the list of [contributors](https://github.com/hjohnson12/KanbanBoardUWP/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
