# Last Across the Finish Line

"Last Across the Finish Line" is an example application which showcases a
pattern for tracking asynchronous batch workers and notifying a user that
when all the workers have completed.

This was described in detail in a three part [blog post][1] from one of the
Google App Engine team members.

The [pipeline API][2] is a higher level way to orchestrate task queues (this
has been merged since in the mapreduce API we ship with the SDK).

There is also a third-party library -- [fantasm][3] -- for doing similar
task queue orchestration.

## Products
- [App Engine][4]

## Language
- [Python][5]

## APIs
- [NDB Datastore API][6]

## Dependencies
- [webapp2][7]
- [jinja2][8]


[1]: http://blog.bossylobster.com/2012/08/last-to-cross-finish-line-part-one.html
[2]: http://code.google.com/p/appengine-pipeline/
[3]: http://code.google.com/p/fantasm/
[4]: https://developers.google.com
[5]: https://python.org
[6]: https://developers.google.com/appengine/docs/python/ndb/
[7]: http://webapp-improved.appspot.com/
[8]: http://jinja.pocoo.org/docs/
