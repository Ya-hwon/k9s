<img src="https://raw.githubusercontent.com/Ya-hwon/k9s/master/assets/k9s_small.png" align="right" width="200" height="auto"/>

# Release v0.15.2

## Notes

Thank you to all that contributed with flushing out issues and enhancements for K9s! I'll try to mark some of these issues as fixed. But if you don't mind grab the latest rev and see if we're happier with some of the fixes! If you've filed an issue please help me verify and close. Your support, kindness and awesome suggestions to make K9s better is as ever very much noticed and appreciated!

Also if you dig this tool, please make some noise on social! [@kitesurfer](https://twitter.com/kitesurfer)

On Slack? Please join us [K9slackers](https://join.slack.com/t/k9sers/shared_invite/enQtOTA5MDEyNzI5MTU0LWQ1ZGI3MzliYzZhZWEyNzYxYzA3NjE0YTk1YmFmNzViZjIyNzhkZGI0MmJjYzhlNjdlMGJhYzE2ZGU1NjkyNTM)

---

## Mo PortForwards...

While putting together the [OpenFeeZ video](https://youtu.be/7Fx4XQ2ftpM), I've noticed a few issues with port-forwards and benchmarks. While I was doing surgery on that carp, figured why not go pull a full monty on port-forwards and enable for other controller like resources such as deployments, statefulsets and daemonsets. So now you can set up port-forwards on any of these using `shift-f`. This exhibits the same mechanics as service based port-forwards ie pick a container port from pods matching the controller selector.

## Resolved Bugs/Features/PRs

---

<img src="https://raw.githubusercontent.com/Ya-hwon/k9s/master/assets/imhotep_logo.png" width="32" height="auto"/> © 2020 Imhotep Software LLC. All materials licensed under [Apache v2.0](http://www.apache.org/licenses/LICENSE-2.0)
