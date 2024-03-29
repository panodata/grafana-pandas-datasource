#################################
Grafana pandas datasource backlog
#################################


**********
Priority 1
**********
- [x] Adjust HTML index page
- [x] Add documentation for installation on Windows
- [x] Improve documentation
- [x] Add logging
- [x] Format code with black and isort
- [x] Publish new release


**********
Priority 2
**********
- [o] Add an example for the "rendering HTML panels" feature,
  see https://github.com/panodata/grafana-pandas-datasource/issues/12
- [o] Add software tests
- [o] Integrate sinewave demo into codebase as "builtin:sinewave-demo"
- [o] Expand sinewave example from ``sine_wave:24`` to, e.g. ``fn:sin(freq=24)``.
- [o] Use ``add_panel_reader``, see https://github.com/panodata/grafana-pandas-datasource/pull/3


**********
Priority 3
**********
- [o] Migrate to https://github.com/marcusolsson/grafana-json-datasource
- [o] Upgrade to Flask 2
- [o] Migrate from Poetry to native pip
