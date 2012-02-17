#Greener
##A Feature Friday app

Greener is an application for tracking programmers that are pairing together.  

It consists of a simple interface where an anonymous visitor to the site can choose two users and mark them as paired.  Later, that visitor can find the pair from a list of paired users and mark them as unpaired.

In addition, visitors can "like" users by clicking on a button. A page exists where visitors can see users sorted by the number of likes that they have.

Here's the features to implement in time for demo at the 2:00 meeting:

1. Install redis on your workstation and configure the app to use it
2. Get your app to store session data in Redis (and confirm that it's working - we gotta handle the load!)
3. Using Redis sets, update your app so that users can be paired. [hint](http://jimneath.org/2011/03/24/using-redis-with-ruby-on-rails.html)
4. Using Redis, implement a like button (it doesn't need to use ajax)
5. Create a "like" page that retrieves the values from Redis and displays them
6. Update your app to use a RedisToGo account instead of your local Redis install

Each of these features has been entered as a Github issue.  As you commit to the repo, be sure to reference these issues in your commit messages.  For more info on how to do this, check out [this blog article](https://github.com/blog/831-issues-2-0-the-next-generation).