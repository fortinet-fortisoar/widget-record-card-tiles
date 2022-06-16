# Card Tiles

Displays a list of records in the Card Tiles view.

An example of using the card tiles widget would be displaying a list of workspaces in the Card Tile view on the Threat Intelligence tab of the Threat Intel Management page.

## Version Information

**Version**: 1.0.0

**Certified**: Yes

**Publisher**: Fortinet  

**Compatibility**: 7.2.0 and later

**Applicable**: View Panel and Listing View

## Card Tiles Views

**Card Tiles Edit View**:

<img src="https://raw.githubusercontent.com/fortinet-fortisoar/widget-record-card-tiles/release/1.0.0/docs/media/card-tiles-edit-view.png" alt="Editing the Card Tile Widget" style="border: 1px solid #A9A9A9; border-radius: 4px; padding: 10px; display: block; margin-left: auto; margin-right: auto;">

**Card Tiles - Workspaces Listing**:

<img src="https://raw.githubusercontent.com/fortinet-fortisoar/widget-record-card-tiles/release/1.0.0/docs/media/card_tiles_view_workspaces.png" alt="Workspace listing in the Card Tile View" style="border: 1px solid #A9A9A9; border-radius: 4px; padding: 10px; display: block; margin-left: auto; margin-right: auto;">

## Card Tiles Settings

Provide the following details to customize the Card Tiles widget to suit your requirements:

| Fields                         | Description                              |
| ------------------------------ | ---------------------------------------- |
| Title                          | Specify the heading or title that you want to give to the records in the card tiles view. |
| Data Source                    | Select the data source (module) whose records list you want to view in card tiles. For example, Workspaces. |
| Max Record Limit               | Select the maximum records that you can view in card tiles on a particular page. |
| **Select Card Fields Section** | **Specify the fields that you want to add to the card tiles.** |
| Card Header                    | Select the field whose value you want to set as the header of the card. For example, if you select **Status**, then the card will display the status that has been set for that particular record, such as Active, Draft, etc. as the header of the card. |
| Card Title                     | Select the field whose value you want to set as the title of the card. For example, if you select **Name**, then the card will display the value that is set as the name of the record such as `Need details on APT 45` as the title of the card. |
| Subtitle 1                     | Select the field whose value you want to set as the first subtitle in the card. For example, if you select **Setup by**, then the card will display the username such as `CS Admin` of the user who has set up the workspace record. |
| Subtitle 2                     | Select the field whose value you want to set as the second subtitle in the card. For example, if you select **Created On**, then the card will display the DateTime of setting up the workspace record. |
| Card Details                   | Select the field whose value you want to set for additional details in the card. For example, if you select **Description**, then the card will display the contents of the description that has been added to the workspace record. |
| Show Icon                      | Select this option to display an icon that represents the record on the card. You can choose an icon from the icons drop-down list. |
| Card Left Border               | Select the field whose value you want to set as the left border of the card if the selected field's options contain defined color codes. For example, if you select **Status**, and if the Status picklist has defined color codes for its options, then the cards' left border gets colored with the status that is set for that record. For example, the left border of the card is set to 'green' if the record's status field is set to 'Active', or the left border of the card is set to 'grey' if the record's status field is set to 'Draft'. |
| Filter Criteria                | Specify the filter criteria (optionally) for displaying records in the card tile view on a particular page. For example, to display only those records whose Status is Active, you can add a filter criterion such as `Status Equals Action`. |
| Default Sort                   | Specify the sorting parameters (optionally) for displaying records in the card tile view on a particular page. |

