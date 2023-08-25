# Alfred Gitlab

Quickly navigate to GitLab projects in [Alfred 3][alfred].

![][sample]

## Setup and Usage
* Generate a GitLab personal access token (https://gitlab.com/profile/personal_access_tokens) then run `glsetkey <yourkey>`
* (Optionally) Tell it where the GitLab API you want to connect to is by running `glseturl https://<host>/api/v4/projects`
  * Defaults to GitLab.com's public API
* search for projects with `gl <search>`

### Sub-Page Navigation
![][sub-page]
After selecting a repository, enter or click on it to see its overview page, if instead you CMD-ENTER you will see the sub-page action.

## Notes
By default, we will only show projects which you are a member of.

## TODOs
* Optionally, allow you to search for non-membership repos
* Add alfred-workflow updater notifications
* Clean up 

# Thanks, License, Copyright

- The [Alfred-Workflow][alfred-workflow] library is used heavily, and it's wonderful documentation was key in building the plugin.
- The GitLab icon is used, care of GitLab.

All other code/media are released under the [MIT Licence][license].

[alfred]: http://www.alfredapp.com/
[alfred-workflow]: http://www.deanishe.net/alfred-workflow/
[wf-vars]: https://www.alfredapp.com/help/workflows/advanced/variables/
[license]: src/LICENSE.txt
[sample]: docs/sample.png
[sub-page]: docs/sub-page.png