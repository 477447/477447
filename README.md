- 👋 Hi, I’m @477447
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
477447/477447 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->print("Hello,World!!!")
def("- name: Publish production app")
def("run: yarn run publish")
def("env:")
    def("npm_config_arch:${{matrix,arch}}")
    def("DESKTOPBOT_TOKEN:${{secrets,DESKTOPBOT_TOKEN}}")
    def("WINDOWS_CERT_PASSWORD:${{secrets,WINDOWS_CERT_PASSWORD}}")
    def("KEY_PASSWORD:${{secrets,KEY_PASSWORD}}")
    TXT.docx
    
gh gist clone
Clone a gist locally

Synopsis
Clone a GitHub gist locally.

A gist can be supplied as argument in either of the following formats:

by ID, e.g. 5b0e0062eb8e9654adad7bb1d81cc75f
by URL, e.g. "https://gist.github.com/OWNER/5b0e0062eb8e9654adad7bb1d81cc75f"
Pass additional 'git clone' flags by listing them after '--'.

gh gist clone <gist> [<directory>] [-- <gitflags>...]
    
gh gist clone <gist> [<directory>] [-- <gitflags>...]
    
    trunk
    
    
    $ gh repo view
View repository READMEs.

  
$ gh repo view
cli/cli
GitHub’s official command line tool

GitHub CLI

gh is GitHub on the command line. It brings pull requests, issues, and other GitHub concepts to the terminal next to where you are already working with git and your code.

Image: screenshot of gh pr status → https://user-images.githubusercontent.com/98482/84171218-327e7a80-aa40-11ea-8cd1-5177fc2d0e72.png

View this repository on GitHub: https://github.com/cli/cli

"[you need to create a special code]"
"[for me to use this code]"

"[l was able to get every]"
"[day up to 9000.00 USD]"

"[it is very important that this is within the law]"
"[For example l will copy]"

"[various Licenses or others]"
"[users could use]"

"[with this code but in this case l was getting]"
"[the percentage of their income is that]"

"[in case they copy my code]"
"[l hope that your experienced staff]"

"[and specialists will be able to implement this in full]"
"[volume!]"

import (
      "fmt"
      "os"
      "path/filepath"
      "string"
      
      "github.com/cli/internal/docs"
      
print("Hello,World!!!")

You can view, comment on, or merge this pull request online at:
  https://github.com/cli/cli/pull/3460

Commit Summary
rebase with trunk
Add a note about the style of git tests
Merge pull request #3036 from cli/pr-merge-no-commits
Merge pull request #3024 from cli/normalize-pr-commands
:nail_care: cleanup `gist edit -a` feature
Improve error handling and avoid writing confirmation to stdout
Switch `repo list` to query via `graphql` package
Avoid having to first query for username in `repo list`
Isolate flag processing tests in `repo list`
Merge pull request #2997 from g14a/feature/add-files-to-gist
Enable pager for `repo list` output
Enable filtering `repo list` by coding language
Add ability to filter by archived in `repo list`
Merge pull request #2953 from cristiand391/add-repo-list
Add information about AUR
Add tests for checking out repository after creating from template
Add test for `api --cache` behavior
Allow caching HTTP 204 responses
Merge remote-tracking branch 'origin' into api-cache
Fix markdown link
some text tweaks
Merge remote-tracking branch 'origin/trunk' into interactive-gist-view
just hide empty descriptions
Merge pull request #3008 from ganboonhong/interactive-gist-view
Merge pull request #3010 from cli/api-cache
Exit with status code "2" on user cancellation errors
Merge remote-tracking branch 'origin' into cancel-error-status
Disallow operating on binary files in gist
Simplify looking up binary types in gist
Sort gist files case-insensitively
Disallow binary files with `gist edit -a`
Tweak language
Merge pull request #3059 from fossdd/patch-1
Merge pull request #2991 from cli/repo-create-prompt-change
Merge pull request #3018 from castaneai/pr-create-body-file
Merge remote-tracking branch 'origin' into api-template
Add template functions, documentation, tests
Use absolute path when configuring gh as git credential
Merge remote-tracking branch 'origin/api-template' into api-jq
Add documentation and tests for `api --filter`
Add the `api --preview` flag to opt into GitHub API previews
Merge pull request #3077 from cli/api-preview
Formalize `gh` process exit codes
Read `Executable` from factory instead of from stdlib
Merge pull request #3023 from cli/cancel-error-status
Merge pull request #3075 from cli/credential-helper-absolute
Merge remote-tracking branch 'origin' into api-template
Add flag parsing test for `api --template`
Add more `api --template` tests
Assert that `executeTemplate` is invoked
Merge remote-tracking branch 'origin/api-template' into api-jq
Change the `api --filter` flag to `api --jq`
Add test for `api --jq`
Declare `--jq`, `--template`, `--silent` options mutually exclusive
Avoid checking for new releases when authenticating git
Merge pull request #3011 from cli/api-template
Merge pull request #3012 from cli/api-jq
Merge pull request #3083 from cli/update-notice-redirect
Merge pull request #3042 from g14a/bug/gist-binary-files
Add additions and deletions in pr view
Add additions and deletions in pr view raw as well
reduce arg length to fprintf
add tests for additions and deletions
fix typo in docs of `alias` command
Fix a typo in gh api
Merge pull request #3182 from educhastenier/patch-1
Merge pull request #3183 from kidonng/patch-1
Merge pull request #3086 from g14a/feature/diffstat-pr
add workflow
rename
meh
grep tweaks
fix missing PRAUTHOR and add TODO
Ensure that table printer fills the full width of the terminal
Ensure that `ssh-key list` uses the full width of the terminal
Accept `--body-file` flag if `--body` is supported
Remove unnecessary `BodyFile` field
Merge pull request #3192 from cristiand391/add-body-file-flag
Actions Support Phase 1 (#2923)
workflow list (#3245)
Allow retrying HTTP/2 uploads for release assets
Merge pull request #3253 from cli/http2-upload-retry
Refactor use of glamour to allow style overrides (#3243)
Pass web browser to each individual command
Add back isolated tests for issue/PR lookup by argument
add search feature in listing issues
:nail_care: cleanup switching to search mode in `issue list`
add generic search naming for issues and PRs @samcoe
Add a unified GitHub Search query builder
Merge pull request #3196 from g14a/feature/search-issues
Import PR list API implementation to `pr/list` package
Add `pr list --search`
Add `pr list --author` filter
Add tests for `listPullRequests`
WIP fix filter
BREAKING: lookup all issue/PR labels with "AND" instead of "OR" combinator
Unify checking whether search filters were passed by the user
Remove implicit `sort:created-desc` sort clause for `pr list`
Merge pull request #3294 from cli/pr-search
gh workflow {enable, disable}
bonus: bump list limit
red check for disabling
Merge pull request #3267 from cli/workflow-toggle
support --workflow in run list
Improve PR lint script
Dynamically resolve the column ID for "Needs review"
share run header printing
share job rendering code
share annotation printing
share prForRun
Merge pull request #3323 from cli/share-run-view
Merge pull request #3318 from cli/list-by-workflow
Default to GHES host if only GHES is authenticated (#3286)
Merge pull request #3295 from cli/labels-and-combinator
Merge pull request #3200 from cli/table-widths
Merge pull request #3279 from cli/browser-refactor
Fix tests broken by incompatible merges
Add `issue transfer` command
:nail_care: cleanup issue transfer
Merge pull request #3258 from g14a/feature/transfer-issue
Disable preview option in prompts if URL size is too long
:nail_care: cleanup URL length checking
Merge pull request #3271 from cristiand391/disable-preview-long-url
Fix crash when generating man pages
Add tests for manual pages generation
small refactor around prompting for runs
Merge pull request #3332 from cli/run-prompt-refactor
fix premature return while forking repo non interactively
Treat unrecognized PR Checks statuses as "pending"
Merge pull request #3193 from cli/prautomation
Fix pr automation workflow
Merge pull request #3336 from cli/pr-checks-crash
absorb gh job view into gh run view
remove job command, update gh actions text
add test for non tty fork
Merge branch 'trunk' of https://github.com/cli/cli into fix/nontty-fork
add GetRunsWithFilter
gh run rerun
Add section in help for actions commands
Merge pull request #3334 from g14a/fix/nontty-fork
Quick fix: respect default hostname when parsing `owner/repo` pairs
Fix PR automation workflow
Merge pull request #3341 from cli/actions-help-section
Add tests for quick fix
Merge pull request #3347 from cli/hostname-override
no need to hide this
Merge pull request #3338 from cli/merge-job-run-view
Merge pull request #3333 from cli/run-rerun
workflow view
Yaml to YAML
Address PR comments
Add `run download` command for downloading workflow artifacts
Add ARTIFACTS information to `run view`
Restore Go < 1.16 compatibility
Merge remote-tracking branch 'origin' into artifact-download
Fix test after merge
support --web for run view
support --web when focusing a job
Merge pull request #3337 from cli/workflow-view-2
tweak error text
Merge pull request #3357 from cli/run-flags
make ExitStatus reflect focused job
Merge pull request #3330 from cli/man-gen-test
support --log for runs
xplatform oops
sigh
gh run watch
Display all run logs
Renaming and cleanup
review feedback
Merge pull request #3324 from cli/run-watch
Have StringSet preserve original order of values
Address `run download` feedback
Move `Artifact` to the "shared" package
Add tests for artifact rendering in `run view`
Merge remote-tracking branch 'origin' into artifact-download
make test windows friendly
add an example
Merge pull request #3349 from cli/artifact-download
golf
obsolete TODO
Merge branch 'trunk' into display-all-the-logs
Merge pull request #3368 from cli/display-all-the-logs
gh workflow run
review feedback
share workflow content getting code
Add flag log-failed to display only logs of failed steps
linter
Tweak build scripts to enable cross-compiling
tweak wording
review feedback
review feedback
Moar memory
linter
add specific unit tests for findInputs
correct Examples
Merge pull request #3379 from cli/failed-logs
Merge pull request #3303 from cli/workflow-run
Merge pull request #3383 from cli/build-env
update glamour to version which includes emoji support
go mod tidy
Enable emoji in markdown
remove previous emoji workaround
handle array type for on: in workflow file
Merge pull request #3404 from cli/on-array
make gh actions output Real
linter appeasement
add gh run download
workflow view
just check nil
Merge pull request #3405 from cli/gh-actions
Use `--exit-status` instead of `-e` in example
Merge pull request #3407 from skedwards88/patch-1
Add time since run to run selection survey options
Fix trying to read from non-existent log file
make run log cache key unique
Merge pull request #3408 from cli/fix-run-selection
Fix secrets in PR automation being available to PR from forks
Extract JSON filtering functionality from `gh api`
Add note about current branch detection
Fix extracting workflow artifact to a relative path
Merge pull request #3413 from cli/run-download-fix
Move issue list queries to under the `issue/list` package
Add `--json` export flag for issues and pull requests
Merge remote-tracking branch 'origin' into json-format
Restructure PullRequestStatus function
Add `pr status --json` support
Add `issue status --json` support
fix small bug with startup_failure conclusion
incorporate wording feedback
unhide actions commands
annotation fixes
bump run list limit
minor usage improvements
Merge pull request #3412 from cristiand391/current-branch-help-text
Expose more fields for PR JSON export
Change JSON Exporter to an interface
placeholder consistency
Merge pull request #3418 from cli/startup-failure
Add `gh help formatting` topic & link to it from commands with JSON output
Tests for GraphQL query builder and JSON exporter
Merge remote-tracking branch 'origin' into json-format
Fix assigning null Exporter
Fix `pr view` tests broken by `createdAt` → `submittedAt` switch
Disallow unsupported values for `--json` flag
Fix whitespace formatting of `issue/pr view` help text
Merge pull request #3414 from cli/json-format
create cache dir
Merge pull request #3429 from cli/log-fail-cache
Merge pull request #3403 from cli/update-glamour
File Changes
A .github/workflows/prauto.yml (77)
M Makefile (17)
M api/cache.go (12)
M api/client.go (96)
M api/client_test.go (64)
A api/export_pr.go (107)
A api/export_pr_test.go (148)
M api/queries_comments.go (16)
M api/queries_issue.go (277)
M api/queries_pr.go (599)
M api/queries_pr_review.go (21)
M api/queries_pr_test.go (84)
M api/queries_repo.go (3)
A api/query_builder.go (188)
A api/query_builder_test.go (39)
M api/reaction_groups.go (34)
M cmd/gen-docs/main.go (61)
A cmd/gen-docs/main_test.go (32)
M cmd/gh/main.go (104)
M context/remote.go (14)
M context/remote_test.go (11)
M docs/install_linux.md (3)
M docs/source.md (24)
A git/fixtures/.gitignore (1)
A git/fixtures/simple.git/HEAD (1)
A git/fixtures/simple.git/config (9)
A git/fixtures/simple.git/index (0)
A git/fixtures/simple.git/logs/HEAD (2)
A git/fixtures/simple.git/logs/refs/heads/main (2)
A git/fixtures/simple.git/objects/4b/825dc642cb6eb9a060e54bf8d69288fbee4904 (0)
A git/fixtures/simple.git/objects/6f/1a2405cace1633d89a79c74c65f22fe78f9659 (0)
A git/fixtures/simple.git/objects/d1/e0abfb7d158ed544a202a6958c62d4fc22e12f (3)
A git/fixtures/simple.git/refs/heads/main (1)
M git/git.go (35)
M git/git_test.go (41)
M go.mod (14)
M go.sum (98)
M internal/authflow/flow.go (20)
A internal/config/config_map.go (99)
M internal/config/config_type.go (415)
M internal/config/from_env.go (13)
A internal/config/from_file.go (318)
M internal/config/stub.go (8)
M internal/ghinstance/host.go (16)
M internal/ghinstance/host_test.go (23)
M internal/ghrepo/repo.go (21)
M internal/ghrepo/repo_test.go (34)
M internal/update/update.go (5)
D pkg/browser/browser.go (80)
D pkg/browser/browser_test.go (75)
A pkg/cmd/actions/actions.go (77)
M pkg/cmd/alias/set/set.go (2)
M pkg/cmd/api/api.go (166)
M pkg/cmd/api/api_test.go (276)
M pkg/cmd/auth/gitcredential/helper.go (16)
M pkg/cmd/auth/gitcredential/helper_test.go (34)
M pkg/cmd/auth/login/login.go (177)
M pkg/cmd/auth/login/login_test.go (98)
M pkg/cmd/auth/refresh/refresh.go (22)
D pkg/cmd/auth/shared/client.go (34)
M pkg/cmd/auth/shared/git_credential.go (64)
M pkg/cmd/auth/shared/git_credential_test.go (114)
A pkg/cmd/auth/shared/login_flow.go (208)
A pkg/cmd/auth/shared/login_flow_test.go (155)
A pkg/cmd/auth/shared/oauth_scopes.go (90)
A pkg/cmd/auth/shared/oauth_scopes_test.go (79)
A pkg/cmd/auth/shared/ssh_keys.go (119)
M pkg/cmd/auth/status/status.go (8)
M pkg/cmd/auth/status/status_test.go (10)
M pkg/cmd/factory/default.go (16)
M pkg/cmd/factory/http.go (2)
M pkg/cmd/factory/remote_resolver.go (67)
M pkg/cmd/factory/remote_resolver_test.go (290)
M pkg/cmd/gist/clone/clone.go (6)
M pkg/cmd/gist/create/create.go (49)
M pkg/cmd/gist/create/create_test.go (21)
M pkg/cmd/gist/delete/delete.go (22)
M pkg/cmd/gist/delete/delete_test.go (4)
M pkg/cmd/gist/edit/edit.go (85)
M pkg/cmd/gist/edit/edit_test.go (82)
D pkg/cmd/gist/list/http.go (88)
M pkg/cmd/gist/list/list.go (17)
M pkg/cmd/gist/list/list_test.go (22)
M pkg/cmd/gist/shared/shared.go (114)
M pkg/cmd/gist/shared/shared_test.go (35)
M pkg/cmd/gist/view/view.go (128)
M pkg/cmd/gist/view/view_test.go (161)
M pkg/cmd/issue/comment/comment.go (14)
M pkg/cmd/issue/comment/comment_test.go (43)
M pkg/cmd/issue/create/create.go (97)
M pkg/cmd/issue/create/create_test.go (199)
A pkg/cmd/issue/edit/edit.go (250)
A pkg/cmd/issue/edit/edit_test.go (437)
M pkg/cmd/issue/issue.go (4)
M pkg/cmd/issue/list/fixtures/issueList.json (74)
A pkg/cmd/issue/list/fixtures/issueSearch.json (54)
A pkg/cmd/issue/list/http.go (229)
R pkg/cmd/issue/list/http_test.go (20)
M pkg/cmd/issue/list/list.go (115)
M pkg/cmd/issue/list/list_test.go (445)
A pkg/cmd/issue/shared/lookup_test.go (102)
M pkg/cmd/issue/status/status.go (33)
A pkg/cmd/issue/transfer/transfer.go (114)
A pkg/cmd/issue/transfer/transfer_test.go (147)
M pkg/cmd/issue/view/view.go (19)
M pkg/cmd/issue/view/view_test.go (97)
M pkg/cmd/pr/checkout/checkout.go (2)
M pkg/cmd/pr/checks/checks.go (21)
M pkg/cmd/pr/checks/checks_test.go (39)
M pkg/cmd/pr/comment/comment.go (23)
M pkg/cmd/pr/comment/comment_test.go (49)
M pkg/cmd/pr/create/create.go (80)
M pkg/cmd/pr/create/create_test.go (188)
M pkg/cmd/pr/diff/diff.go (9)
A pkg/cmd/pr/edit/edit.go (338)
A pkg/cmd/pr/edit/edit_test.go (611)
M pkg/cmd/pr/list/fixtures/prList.json (50)
M pkg/cmd/pr/list/fixtures/prListWithDuplicates.json (38)
A pkg/cmd/pr/list/http.go (228)
A pkg/cmd/pr/list/http_test.go (163)
M pkg/cmd/pr/list/list.go (102)
M pkg/cmd/pr/list/list_test.go (24)
A pkg/cmd/pr/merge/http.go (138)
M pkg/cmd/pr/merge/merge.go (212)
M pkg/cmd/pr/merge/merge_test.go (416)
M pkg/cmd/pr/pr.go (2)
M pkg/cmd/pr/ready/ready.go (9)
M pkg/cmd/pr/review/review.go (23)
M pkg/cmd/pr/review/review_test.go (40)
M pkg/cmd/pr/shared/commentable.go (10)
M pkg/cmd/pr/shared/comments.go (6)
A pkg/cmd/pr/shared/editable.go (371)
A pkg/cmd/pr/shared/lookup_test.go (108)
M pkg/cmd/pr/shared/params.go (94)
M pkg/cmd/pr/shared/params_test.go (2)
M pkg/cmd/pr/shared/preserve.go (6)
M pkg/cmd/pr/shared/survey.go (54)
A pkg/cmd/pr/shared/templates.go (261)
A pkg/cmd/pr/shared/templates_test.go (74)
M pkg/cmd/pr/status/status.go (43)
M pkg/cmd/pr/view/fixtures/prView.json (4)
M pkg/cmd/pr/view/fixtures/prViewPreview.json (2)
M pkg/cmd/pr/view/fixtures/prViewPreviewClosedState.json (2)
M pkg/cmd/pr/view/fixtures/prViewPreviewDraftState.json (2)
M pkg/cmd/pr/view/fixtures/prViewPreviewDraftStatebyBranch.json (4)
M pkg/cmd/pr/view/fixtures/prViewPreviewMergedState.json (2)
M pkg/cmd/pr/view/fixtures/prViewPreviewReviews.json (10)
M pkg/cmd/pr/view/fixtures/prViewPreviewSingleComment.json (2)
M pkg/cmd/pr/view/fixtures/prViewPreviewWithMetadataByBranch.json (4)
M pkg/cmd/pr/view/fixtures/prViewPreviewWithMetadataByNumber.json (2)
M pkg/cmd/pr/view/fixtures/prViewPreviewWithReviewersByNumber.json (2)
M pkg/cmd/pr/view/fixtures/prView_EmptyBody.json (4)
M pkg/cmd/pr/view/view.go (27)
M pkg/cmd/pr/view/view_test.go (174)
M pkg/cmd/release/create/create.go (10)
M pkg/cmd/release/delete/delete.go (2)
M pkg/cmd/release/shared/upload.go (1)
M pkg/cmd/release/view/view.go (10)
M pkg/cmd/repo/clone/clone.go (7)
M pkg/cmd/repo/create/create.go (117)
M pkg/cmd/repo/create/create_test.go (36)
M pkg/cmd/repo/fork/fork.go (26)
M pkg/cmd/repo/fork/fork_test.go (201)
M pkg/cmd/repo/garden/http.go (6)
A pkg/cmd/repo/list/fixtures/repoList.json (40)
A pkg/cmd/repo/list/fixtures/repoSearch.json (37)
A pkg/cmd/repo/list/http.go (235)
A pkg/cmd/repo/list/http_test.go (162)
A pkg/cmd/repo/list/list.go (181)
A pkg/cmd/repo/list/list_test.go (369)
M pkg/cmd/repo/repo.go (2)
M pkg/cmd/repo/view/view.go (18)
M pkg/cmd/repo/view/view_test.go (10)
M pkg/cmd/root/help.go (21)
M pkg/cmd/root/help_reference.go (2)
M pkg/cmd/root/help_topic.go (25)
M pkg/cmd/root/root.go (8)
A pkg/cmd/run/download/download.go (190)
A pkg/cmd/run/download/download_test.go (0)
A pkg/cmd/run/download/fixtures/myproject.zip (0)
A pkg/cmd/run/download/http.go (0)
A pkg/cmd/run/download/http_test.go (0)
A pkg/cmd/run/download/zip.go (0)
A pkg/cmd/run/download/zip_test.go (0)
A pkg/cmd/run/list/list.go (0)
A pkg/cmd/run/list/list_test.go (0)
A pkg/cmd/run/rerun/rerun.go (0)
A pkg/cmd/run/rerun/rerun_test.go (0)
A pkg/cmd/run/run.go (0)
A pkg/cmd/run/shared/artifacts.go (0)
A pkg/cmd/run/shared/presentation.go (0)
A pkg/cmd/run/shared/shared.go (0)
A pkg/cmd/run/shared/shared_test.go (0)
A pkg/cmd/run/shared/test.go (0)
A pkg/cmd/run/view/fixtures/run_log.zip (0)
A pkg/cmd/run/view/view.go (0)
A pkg/cmd/run/view/view_test.go (0)
A pkg/cmd/run/watch/watch.go (0)
A pkg/cmd/run/watch/watch_test.go (0)
M pkg/cmd/secret/list/list.go (0)
M pkg/cmd/secret/list/list_test.go (0)
M pkg/cmd/secret/remove/remove.go (0)
M pkg/cmd/secret/remove/remove_test.go (0)
M pkg/cmd/secret/set/http.go (0)
M pkg/cmd/secret/set/set.go (0)
M pkg/cmd/secret/set/set_test.go (0)
A pkg/cmd/ssh-key/add/add.go (0)
A pkg/cmd/ssh-key/add/add_test.go (0)
A pkg/cmd/ssh-key/add/http.go (0)
M pkg/cmd/ssh-key/list/http.go (0)
M pkg/cmd/ssh-key/list/list.go (0)
M pkg/cmd/ssh-key/list/list_test.go (0)
M pkg/cmd/ssh-key/ssh-key.go (0)
A pkg/cmd/workflow/disable/disable.go (0)
A pkg/cmd/workflow/disable/disable_test.go (0)
A pkg/cmd/workflow/enable/enable.go (0)
A pkg/cmd/workflow/enable/enable_test.go (0)
A pkg/cmd/workflow/list/list.go (0)
A pkg/cmd/workflow/list/list_test.go (0)
A pkg/cmd/workflow/run/run.go (0)
A pkg/cmd/workflow/run/run_test.go (0)
A pkg/cmd/workflow/shared/shared.go (0)
A pkg/cmd/workflow/shared/test.go (0)
A pkg/cmd/workflow/view/http.go (0)
A pkg/cmd/workflow/view/view.go (0)
A pkg/cmd/workflow/view/view_test.go (0)
A pkg/cmd/workflow/workflow.go (0)
M pkg/cmdutil/args.go (0)
M pkg/cmdutil/errors.go (0)
M pkg/cmdutil/factory.go (0)
A pkg/cmdutil/file_input.go (0)
A pkg/cmdutil/json_flags.go (0)
A pkg/cmdutil/json_flags_test.go (0)
A pkg/cmdutil/web_browser.go (0)
A pkg/export/filter.go (0)
A pkg/export/filter_test.go (0)
A pkg/export/template.go (0)
A pkg/export/template_test.go (0)
A pkg/githubsearch/query.go (0)
M pkg/iostreams/color.go (0)
A pkg/iostreams/console.go (0)
A pkg/iostreams/console_windows.go (0)
M pkg/iostreams/iostreams.go (0)
M pkg/markdown/markdown.go (0)
M pkg/markdown/markdown_test.go (0)
A pkg/set/string_set.go (0)
A pkg/set/string_set_test.go (0)
M script/build.go (0)
M test/helpers.go (0)
M utils/table_printer.go (0)
M utils/utils.go (0)
Patch Links:
https://github.com/cli/cli/pull/3460.patch
https://github.com/cli/cli/pull/3460.diff
—
You are receiving this because you are subscribed to this thread.
Reply to this email directly, view it on GitHub, or unsubscribe.
