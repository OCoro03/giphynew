I had issues getting my buttons created and retrieving data from the giphy website.
I had started by using the following code to resolve the initial problem.
$("#submit").on("click", function(){
      var search = ("#search-box").val().trim();
      var newButton = $("<button>");

        // newButton.attr("id", "button-");
        $("#buttons").text(search);
    })
Here I am signaling the submit button on my HTML page and creating a button that should appear next to rest of the buttons I already have on my page.
