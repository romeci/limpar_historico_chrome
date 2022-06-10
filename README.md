// Tested on Chrome Version 72.0.3626.119 (Official Build) (64-bit)
// 1) Open Chrome browser history.
// 2) Search for specific history you want to delete.
// 3) Cut-and-paste the code below in the Chrome Browser console.
// Enjoy!


(function (){
let historyApp = document.getElementById("history-app");
historyApp.items[0].selectAllItems();

// Delete history with a popup confirmation prompt
historyApp.deleteSelected();

// Delete with no prompt
// historyApp.items[0].deleteSelected_()  

})();
