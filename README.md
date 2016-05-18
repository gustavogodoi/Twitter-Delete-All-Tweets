<pre>
# Twitter-Delete-All-Tweets
// go to https://twitter.com/your-username, and enter the following into the developer console:
for(var i = 1; i < 500; i++){ // just do it a bunch
  // Remove Retweets
  document.getElementsByClassName("ProfileTweet-actionButtonUndo")[i].click();
  document.getElementsByClassName("js-close")[0].click();
  // Delete tweets
  document.getElementsByClassName("js-actionDelete")[i].childNodes[1].click();
  document.getElementsByClassName("delete-action")[0].click()
}
</pre>
