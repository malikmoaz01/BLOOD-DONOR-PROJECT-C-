Blood Donor System

Introduction:
The Blood Donor System is a program developed in C++ to manage donor records for a blood donation society. This system allows users to perform various operations such as adding donors, searching for donors by name or blood group, updating donor records, removing donor records, and viewing the list of donors.

Features:

    Add a Member: Users can input details of donors including their name, blood group, and city, and add them to the system's records.
    Search by Name: Users can search for donors by their name and retrieve their details.
    Search by Blood Group: Users can search for donors by their blood group and retrieve their details.
    Update Donor Record: Users can update the details of a donor's record, including their name, blood group, and city.
    Remove Donor Record: Users can remove a donor's record from the system.
    View List of Donors: Users can view the list of all donors along with their details.

Code Structure:

    The program utilizes a structure named donor to store information about each donor, including their name, blood group, and city.
    Functions such as input, searchName, searchblood, update, remove, and read are defined to perform various operations on the donor records.
    The main function acts as the driver program, allowing users to choose different options and interact with the system.

Usage:

    Upon running the program, users are presented with a menu displaying different options.
    Users can select an option from the menu to perform the corresponding operation.
    The program prompts users for input as needed and provides relevant output based on the chosen operation.
    Users can navigate through the menu to add, search, update, remove, or view donor records as required.
    The program continues to execute until the user chooses to exit.

Note:

    The program stores donor records in a text file named "bds_donor_data.txt" and reads from/writes to this file for data persistence.
    Improvements and additional features can be incorporated to enhance the functionality and user experience of the Blood Donor System.
