pcci - puppet community continuous integration
==============================================


An experiment in public beaker testing


requirements: 

* github bot account
* redis-server running
* beefy machine to run tests




application deployment:


right now this is super janky.


follow_pull_requests.py is run by 5 minute cron


8 worker.py's run  (sent to background in shell)


one comment.py is run in the foreground in a tmux


improvement needed!
