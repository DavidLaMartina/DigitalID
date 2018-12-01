# Digital ID tests for Stories 20-23 - WEEK 7 UPDATE

Instructions for Compilation and Execution - Tests1 and Tests2:</br></br>
Stories 20, 21, 22, 23 and updates to HW6 stories:</br>
Tests1.zip</br>
Download zip file and cut or copy to testing directory in OSU Flip</br>
Use separate testing directory for Tests1.zip and Tests2.zip</br>
Unzip contents</br>
Type “make” and press Enter to compile 3 executables:</br>
story1</br>
story2</br>
story_main</br>
NOTE: There are two dummy image files included: front.jpg and back.jpg. These images will display nothing if opened in an image-viewing program. They are meant to allow the user to test the image-adding function, which will alert the user of a failure to add if the specified paths are invalid. As long as these files are contained within the testing directory, the user will receive a successful add notification by entering “front.jpg” and “back.jpg” when prompted for front image and back image, respectively.</br>
Type the name of any of those 3 executables to run the associated testing program.</br>
story1 is an expanded version of last week’s test of the same name. It includes additional diagnostics for the copyID and image-adding functions.</br>
story2 is an expanded version of last week’s test of the same name. It includes an additional sub-menu within the update selection to add image files.</br>
story_main is the fully expanded, menu-based testing program which includes all of the functionality programmed into Digital ID thus far. Additional main menu items include the ability manually add and authenticate the data for a physical ID (choice #4) and the ability to manually initiate the ID authentication process (choice #5).</br>
Instructions for Menu Choice #4, Physical ID Manual Data Entry</br>
When selected, this menu item will display prompts for ID data entry similar to those presented when selected choice #1, “Add ID.” It will also display the “correct” information against which the new information will be validated. To achieve a successful authentication, the user must use the attribute-adding options to enter the displayed set of “correct” information. If the authentication fails, the user may need to update incorrect values, add attributes, or delete attributes whose keys do not match those in the correct set of information.</br>
Instructions for Menu Choice #5, Initiate Authentication for an ID</br>
When selected, this menu will prompt the user to select a specific ID for re-authentication. The same set of “correct” test data from Menu Choice #4 is used as the standard for this option. Thus, to achieve a successful authentication with Choice #5, the user must select the reference number of an ID already populated with that information. Any other set of information will receive a fail.</br>
</br></br>

Stories 7, 10, 13</br>
Tests2.zip</br>
Download zip file and cut or copy to testing directory in OSU Flip</br>
Use separate testing directory for Tests1.zip and Tests2.zip</br>
Unzip contents</br>
Type “make” and press Enter to compile</br>
story7_10_13</br>
Type ./story7_10_13 to run the program</br>
The first prompt will present the Digital ID inspection screen. The preloaded IDs can be viewed by selecting any ID of your choice. Once the selection is then made you are able to view the front ID image. The choices presented to you will be to view the backside of the ID, edit contents, or remove the ID. These selections will be presented for each ID in the wallet.</br>
After the ID viewer is exited, the program will proceed to run the smart card addition unit test. This is an automated process that creates a new wallet with preloaded IDs and then adds two additional IDs with the smart card type. The smart card selection function is then tested by outputting the available smart cards the user can select from. An invalid selection will result in the failure of the smart card selection function, while a valid selection will cause the selection function to pass.</br>


# Digital ID Tests for Stories 1, 2, 3, 4, 14, 15

Instructions for Compilation and Execution:</br>
Stories 1, 2, 3, 4</br>
Stories1-4.zip</br>
Download zip file and cut or copy to testing directory in OSU Flip</br>
Use separate testing directory for each Stories1-4.zip and Stories14-15.zip</br>
Unzip contents</br>
Type “make” and press Enter to compile all 4 executables</br>
story1</br>
story2</br>
extra_test_1</br>
extra_test_2</br>
Type the name of any of those 4 executables to run the associated testing program.</br>
story1, extra_test_1, and extra_test_2 are simple diagnostic runs which test the functions of the ID and ID_collection classes.</br>
story2 is a text-based, menu-based testing program which allows the user to add, remove and update IDs in an ID collection.</br>
</br>
Stories 14, 15</br>
Stories14-15.zip</br>
Download zip file and cut or copy to testing directory is OSU Flip</br>
Use separate testing directory for each Stories1-4.zip and Stories14-15.zip</br>
Unzip contents</br>
Type “make” and press Enter to compile the executable</br>
test_lock</br>
Type the name of the executable (test_lock) to run the associated testing program.</br>
