
n.n.n / 2014-04-14 
==================

  * Merge pull request #2685 from delynn/patch-2
  * Remove mailcatcher
  * Merge pull request #2329 from pstadler/brew-cask
  * Merge pull request #2663 from bobmaerten/docker-autocomplete-updates
  * Merge pull request #2651 from jehrhardt/fix-emacs
  * Merge pull request #2661 from mcornella/fix_title_tab_percent
  * Merge pull request #2659 from simonc/allowing-pow-path-with-spaces
  * Merge pull request #2658 from leifcr/rake-fast-issue
  * Merge pull request #2647 from bobwilliams/master
  * Merge pull request #2656 from philenotfound/master
  * Merge pull request #2652 from lukehorvat/patch-1
  * Merge pull request #2660 from KevinBongart/add-readme-to-rake-fast
  * Merge pull request #2662 from aeriksson/master
  * adding urldecode_json to compliment urlencode_json and updating readme.md; slight tweak to urlencode_json from previous commit
  * adding urlencode_json and associated README.md details
  * Matching autocomplete for Docker v0.9.1
  * Fix broken reverse-menu-complete keybinding.
  * adding the is_json tool and associated readme.md details
  * Escape % in $CMD variable
  * Add README file to rake-fast plugin
  * Allowing path with spaces in pow plugin
  * brew-cask plugin: use spaces instead of tabs
  * Merge branch 'master' of github.com:philenotfound/oh-my-zsh
  * New aliases for 'apt-get' and 'aptitude' as they were overwritten by later aliases
  * adding support for node
  * Adds command line aliases useful for dealing with JSON
  * Updates spectrum.zsh
  * $ZSH is the OMZ installation folder, not configuration
  * mention $ZSH_CUSTOM as suggested in #2295
  * suggest setting $LANG to fix #1286 and fix #1823
  * Fix export syntax of $GREP_OPTIONS
  * Rendering the 'vagrant box (remove|repackage)' completion code independant of Vagrant implementation details.
  * application completion
  * library completion
  * in hindsight, this is probably a bad idea
  * completion of targets
  * instance and cluster completion
  * node completion
  * help command, node completion
  * added _files values for certain options
  * completion options
  * added alias
  * added completions for all known arguments to all known commands
  * apparently, this file must exist for the plugin to load
  * added completion for all asadmin subcommands
  * avoid VCS folders
  * Move example plugin to the custom plugins dir.
  * Add completion for pip install -r - so that it autocompletes requirements filenames
  * Added an <esc> to the begining of everything. I ran something when I was in insert mode once and all it did was shove !args... into the buffer.  <esc> first.
  * Updated the README to include documentation on the postCallVim callout
  * Added an optional callout to the end of the interaction function. I put it in to allow me to put the window focus on MacVim / GVim depending on the different OS I happen to be on
  * Fixed: If you callvim on a non-existant file with a relative path, the CWD of the running gvim process is used, and that's not right.  We use the PWD explicitly instead, in this case
  * A plugin that makes it easier to interact with the (single) running instance of gvim
  * command to restart pow process
  * added powed command to list pow urls
  * fix gnzh theme to detect local rvm installations
  * Added link to wiki page for plugins to README.
  * Add gem build autocompletion
  * `setopt append_history` is not necessary.
  * Plugin: Rake-fast: Support both *nix and Darwin
  * New aliases for 'apt-get' and 'aptitude' as they were overwritten by later aliases
  * Fixed typos + made wording more consistent in zshrc.zsh-template
  * adding xargs -0 to node aliases
  * updated readme.md and using tab char for formatting with node
  * bug fix for node pp_json version
  * Add check for display list equals nil
  * updating README.md
  * adding README.md for jsontools
  * Merge pull request #2563 from bobwilliams/master
  * Merge pull request #2390 from LFDM/updating_spectrum
  * Merge pull request #2645 from ncanceill/template-zshrc
  * Merge remote-tracking branch 'upstream/master'
  * $ZSH is the OMZ installation folder, not configuration
  * mention $ZSH_CUSTOM as suggested in #2295
  * suggest setting $LANG to fix #1286 and fix #1823
  * Merge pull request #2643 from mcornella/patch-1
  * Merge remote-tracking branch 'upstream/master'
  * Fix export syntax of $GREP_OPTIONS
  * Merge pull request #1302 from cybozuty/master
  * Merge pull request #1262 from fred-o/glassfish-plugin
  * Merge pull request #1162 from nXqd/patch-1
  * Merge pull request #1117 from Peeja/move-example-plugin
  * Merge pull request #967 from wjlroe/pip-requirements
  * Merge pull request #1022 from derekwyatt/master
  * Merge pull request #1005 from cmar/powed
  * Merge pull request #995 from wting/fix_gnzh_ruby_detection
  * Merge pull request #990 from tommorris/master
  * Merge pull request #973 from dlee/gem_build
  * Merge pull request #750 from blueyed/history-drop-default-append-history
  * Merge pull request #672 from eMxyzptlk/zsh_reload
  * Merge pull request #662 from walle/add_autocomplete_for_gas
  * Merge pull request #646 from whittle/master
  * Merge pull request #2618 from bdubertret/fix-gwip-norm
  * Merge pull request #2634 from danchenkov/master
  * Merge pull request #2638 from miguelfrde/irb
  * Merge pull request #2605 from mhauserr/patch-1
  * Merge pull request #2615 from erbridge/fix_virtualenvwrapper_lazy
  * Merge pull request #2616 from Bounga/master
  * Merge pull request #2620 from reedriley/master
  * Merge pull request #2619 from korylprince/master
  * Sort bundled commands alphabetically
  * Merge pull request #2440 from m0nah/master
  * Merge pull request #2510 from pavoljuhas/master
  * Merge pull request #2531 from KevinBongart/rake-fast
  * Merge pull request #2637 from aforty/master
  * Merge pull request #2627 from loxley/add_knife_vault_cmd
  * Merge pull request #2631 from AntoineD/master
  * Merge pull request #2639 from jieryn/master
  * add common video formats FLV and WEBM
  * Add irb to the list of bundled commands
  * Merge pull request #1 from KevinBongart/brew-cask
  * Add new brew cask commands
  * Added a forward-delete fallback to bind Delete key
  * atom plugin
  * Aligned comments
  * Update key-bindings.zsh
  * added terminfo keys verification
  * Fix dirpersist plugin
  * Fixed errors if acpitool isn't installed on linux
  * Add chef-vault knife cmd support
  * Add scd plugin for smart change of directory.
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Don't show useless '[]' when chruby_prompt_info is empty
  * Fix gwip alias in git plugin when no files to rm
  * Merge remote-tracking branch 'upstream/master'
  * Don't set RBENV_ROOT to "$HOME/.rbenv" when using Homebrew rbenv
  * Merge pull request #2576 from jeffwilliams/master
  * Merge pull request #2597 from githubhjs/master
  * Don't lazy load the virtualenvwrapper.
  * Merge pull request #2539 from chriswiggins/master
  * Merge pull request #2549 from brandon-beacher/master
  * Merge pull request #2574 from thiagowfx/linux-battery
  * Merge pull request #2603 from docwhat/ssh-agent-hostname
  * Merge pull request #2607 from avonderluft/dev
  * Merge pull request #2613 from Fisiu/ignore-ssh-users
  * Remove copyright information, as per #2588
  * Ignore more users in ssh completion.
  * Merge pull request #2602 from blueyed/use-default-hosts-completion-2
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh into dev
  * add option to show dirty status of current dir
  * Merge remote-tracking branch 'upstream/master'
  * Added v as a keybinding to edit-command-line
  * Merge pull request #2380 from rkh/chruby-gallois
  * Merge pull request #2435 from tompelka/master
  * Merge pull request #2466 from jarus/steeef-virtualenv-fix
  * Merge pull request #2588 from kerimdzhanov/remote-themes-copyright-info
  * Merge pull request #2584 from joukojo/master
  * Merge pull request #2590 from zhouhua015/master
  * Merge pull request #2593 from bobmaerten/typo-docker-plugin
  * Merge pull request #2591 from kevinxucs/remove-extra-aliases
  * ssh-agent: prevent environment file from flapping
  * Fixing a few quirks in the latest installer updates (quoting /Users/robbyrussell/.oh-my-zsh and such). Also mentioining our twitter account after install
  * Use zsh's default for ':completion:*:hosts'
  * Merge pull request #2149 from cristim/master
  * Merge pull request #1355 from F30/key-bindings
  * Merge pull request #2072 from jorge-d/master
  * Merge pull request #2595 from ksamdev/git.io
  * Merge pull request #2421 from LFDM/rails_plugin_fix
  * Merge pull request #2518 from erawk/master
  * Merge pull request #2326 from zakkak/master
  * Merge pull request #1776 from ronshapiro/master
  * Merge pull request #1501 from gambhiro/master
  * Merge pull request #1085 from avit/install-path
  * Merge pull request #650 from tristan0x/emacs
  * Merge pull request #2600 from jontewks/patch-1
  * Update license year
  * Updating README to show the new install URL, which redirects to the raw files on github.
  * Merge pull request #2596 from ryanwmarsh/fixing_bureau_scrollback
  * List pkgs by size
  * Fixes #2467 tab completion scrolls back in terminal when using bureau theme
  * Add github url shortener
  * Fix typo in autocomplete arguments
  * Removed unsolicited aliases.
  * Fix hgsl alias.
  * Merge pull request #2341 from mcornella/title_backticks
  * Document alternate install paths via ZSH variable
  * Abort installer on errors
  * Write install path into .zshrc
  * Reference default install path from ZSH variable
  * Remove all copyright information in themes. Closes #2587
  * Merge pull request #2331 from posva/catimg
  * Merge pull request #2479 from mrbfrank/theme-agnoster
  * Merge pull request #1402 from sergeylukin/master
  * Merge pull request #2565 from theallegedjosh/master
  * Merge pull request #2579 from mfaerevaag/master
  * Merge pull request #2535 from IgorTimoshenko/feature/yii-plugin
  * Merge pull request #2556 from chrisjones-brack3t/fix/git-prompt-1-9
  * Merge pull request #2572 from kevinxucs/sublime-linux-fix
  * Merge pull request #2059 from felipec/fc/gitfast
  * Merge pull request #2529 from emanuelez/patch-1
  * Merge pull request #2525 from lukesteensen/update-go-plugin
  * Merge pull request #2481 from felds/master
  * Merge pull request #2366 from chuancong/patch-1
  * Merge pull request #2322 from dpsk/patch-2
  * Merge pull request #2166 from cap10morgan/no-clobber-rbenv-root
  * Merge pull request #2564 from miry/patch-3
  * Merge pull request #2287 from rumpelsepp/master
  * Merge pull request #2400 from bric3/svn_fast_plugin
  * Merge conflicts with af-magic theme
  * Cleaning up conflict with merge of #2330
  * added mvnjetty alias
  * added aliases for tomcat:run tomcat7:run
  * added mvn-update
  * Updated wd plugin to v0.3.0
  * Added dirhistory plugin.
  * Integrate changes from #1841.
  * added the linux implementation to the battery plugin
  * Fixed sublime plugin behaviors.
  * :panda_face: Added simulator alias for Xcode plugin
  * adding support for node
  * gem push alias and gem yank alias
  * add gem push alias
  * add gem build alias
  * Adds command line aliases useful for dealing with JSON
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * ..a fundamental piece of matter.
  * Merge pull request #2548 from puffnfresh/gitignore-plugin-url
  * Merge pull request #2544 from fduch2k/patch-1
  * Verification of convert inside the function
  * grab last item in list which is the branch instead of relying on position.
  * Much needed PEP8 love. Use spaces, not tabs.
  * Avoid 'title:parse error' with single quotes in $CMD Fixes #2182
  * Revert previous commit, escape %
  * Use single quotes also in $LINE definiton
  * Avoid evaluating special chars in $LINE on title command (fixes #2234)
  * Adieu l'ami.
  * Merge pull request #2541 from puffnfresh/cabal-sandboxes-info
  * Remove mailcatcher from the bundler plugin.
  * Fix remaining broken URL in gitignore function
  * Update gitignore.plugin.zsh
  * Merge pull request #2542 from puffnfresh/gitignore-plugin-url
  * Fix URL to gi (gitignore) function
  * Add cabal_sandbox_info function
  * Update battery plugin to show calculating - OSX
  * Added Yii basic command completion
  * Add rake-fast plugin for fast rake autocompletion
  * Improve oneline logs
  * update golang plugin to match official version
  * remove duplicate 'go' plugin, symlink to 'golang'
  * Updated _brew zsh autocompletion to latest Homebrew upstream
  * Merge pull request #2515 from nupfel/plugins/iwhois
  * Merge pull request #2516 from lukesteensen/patch-1
  * Add 'services' command to homebrew completion
  * provides iwhois command to use CNAMES under whois.geek.nz to find most accurate whois server
  * Add scd plugin for smart change of directory.
  * Merge pull request #2465 from klange/master
  * Merge pull request #2342 from blackjid/master
  * Merge pull request #2402 from bric3/battery_level_gauge
  * highlight the username when root
  * theme agnoster: remove trailing space
  * corrected branch character
  * Merge pull request #2368 from lumbric/master
  * updated url to latest powerline-patched fonts
  * Improve virtualenv prompt in steeef theme
  * Update nyan.plugin.zsh
  * change nyancat telnet server
  * Adds a method that print a battery gauge
  * Add Laravel4 plugin
  * Adding commit hash to branch name in my favorit rjk-repos theme.
  * Fixes _rails_command
  * Renames main plugin function to `svn_prompt_info`
  * Renamed the methods of this script
  * Added further cleanup and svn status information
  * No need to eval in rvm_prompt_info!
  * Heavy refactor of svn-fast-info
  * Merge pull request #2389 from driver2000/patch-1
  * Merge pull request #2398 from phstc/fixes-tmuxinator-plugin-find
  * Inline `parse_svn` to avoid leaky state
  * Report the SVN need upgrade
  * Fixes RPROMPT in af-magic.zsh-theme
  * Renames the file to prompt_info_functions.zsh
  * Adds documentation.
  * Adds all other dummy implementations.
  * new faster SVN plugin
  * Fixes tmuxinator plugin find on OSX
  * add brew-cask plugin
  * Merge pull request #2396 from soluwalana/master
  * escape dashes
  * Update git.plugin.zsh
  * Updates spectrum.zsh
  * Fix bad right prompt placing.
  * Refactors ruby_prompts.zsh
  * Joins ruby prompt files and adds ruby_prompt_info.
  * Adds chruby_prompt_info dummy function.
  * Returns false when rbenv is not found.
  * Returns false when rvm is not found.
  * Fixes rvm_prompt_info() in lib/rvm.zsh
  * add chruby info to gallois theme
  * fix name schema for sudo plugin
  * Add support to command "show"
  * Revert "Cancel update if the current user doesn't have write permissions for the oh-my-zsh directory."
  * Merge pull request #2358 from n-st/master
  * Cancel update if the current user doesn't have write permissions for the oh-my-zsh directory.
  * Prevents oh-my-zsh loading the .zshenv twice
  * Add rdmtc alias for rails plugin.
  * typo fix
  * catimg: fix exit without using source supresses errors from convert whilen converting, as they are usually just warnings
  * Fixed a dirs bug for catimg
  * Fix for virtualenv support - fixes #2328, fixes #2297, resolves #2319
  * catimg plugin allow to print an image to the stdout using convert
  * Improve comments
  * Improve comments
  * Merge pull request #2316 from BBonifield/master
  * Making auto-correction off by default
  * Merge pull request #2303 from petervanderdoes/git-flow-avh
  * Merge pull request #2296 from pstadler/master
  * Update git-flow-avh 1.7.0
  * source ~/.profile only if it exists
  * Merge pull request #2208 from onemouth/master
  * Merge pull request #2173 from jeffrey4l/venv
  * Merge pull request #2159 from pungoyal/master
  * Merge pull request #2176 from dejanlukan/spectrum
  * Merge pull request #2194 from kevinxucs/gitignore-fix
  * Merge pull request #2195 from KevinBongart/command_blacklist_for_bundler_plugin
  * Merge pull request #2215 from posva/rand-quote
  * Merge pull request #2255 from shadyproject/plugin/xcode-support
  * Merge pull request #2258 from amilaperera/master
  * Merge pull request #2262 from mfaerevaag/master
  * Merge pull request #1520 from prooftechnique/master
  * Merge pull request #1574 from adben/master
  * Merge pull request #1683 from mnme/master
  * Merge pull request #1087 from avit/install-template
  * Merge pull request #1136 from koraa/pull_req_fastfile
  * Merge pull request #1135 from koraa/pull_req_sinchar
  * Merge pull request #1134 from koraa/pull_req_helpers
  * Merge pull request #1201 from koraa/pull_req_debian
  * Merge pull request #2088 from Stibbons/gsemet_push_pep_pylint_completion
  * Merge pull request #2086 from Stibbons/gsemet_push_repo
  * Merge pull request #1883 from Stibbons/gsemet_push_source_profile_for_upgrade
  * Merge pull request #1866 from Stibbons/gsemet_push_common_aliases
  * Merge pull request #2003 from dongweiming/update-gem
  * Merge pull request #1950 from dongweiming/add-systemadmin-plugin
  * Merge pull request #1947 from dongweiming/add-sudo
  * Merge pull request #1931 from dongweiming/update-urltools
  * Merge pull request #1942 from dongweiming/update-powify
  * Merge pull request #1940 from dongweiming/update-supervisor
  * Merge pull request #1928 from dongweiming/add-hist-stamp
  * Merge pull request #1927 from dongweiming/modify
  * Merge pull request #1956 from emesix/patch-1
  * Merge pull request #2022 from Zhann/master
  * Merge pull request #2034 from kasperisager/master
  * Merge pull request #2097 from natecox/master
  * Merge pull request #2131 from stevschmid/patch-1
  * Merge pull request #1030 from solnic/master
  * Merge pull request #950 from sonicradish/master
  * Merge pull request #948 from excepttheweasel/master
  * Merge pull request #946 from rach/master
  * Merge pull request #781 from pilif/two-lined-pygmalion
  * Merge pull request #684 from masnick/master
  * Merge pull request #639 from MarcoPeraza/git_unpushed
  * Merge pull request #513 from randy909/fix-edit-cmdline
  * Merge pull request #306 from jtriley/git-prompt
  * Merge pull request #2198 from Larandar/master
  * Merge pull request #2202 from kevinxucs/themes-random
  * Merge pull request #2212 from bsiegel/bundler_bi_function
  * Merge pull request #2222 from jamesoff/fix-battery-plugin
  * Merge pull request #2229 from prubianes/master
  * Merge pull request #2236 from Isquariel/nvm
  * Merge pull request #2270 from michaelorr/slow-git-fix
  * Merge pull request #2272 from TuiKiken/master
  * Merge pull request #2292 from Atem18/master
  * Change `bi` alias to a function
  * Merge remote-tracking branch 'upstream/master'
  * Fixed lines 32, 33, 34 where one 'p' was missing in 'zypper' command.
  * Merge pull request #2290 from jtinfors/master
  * Merge pull request #2242 from sztupy/fix-mvn-color-locale
  * Merge pull request #2252 from henrique2010/master
  * Merge pull request #2254 from Atem18/master
  * Merge pull request #2286 from ych/master
  * Merge pull request #2260 from Stibbons/gsemet_push_sublime3_support2
  * Merge pull request #2285 from dhruvasagar/master
  * Merge pull request #2240 from Kriechi/master
  * Adds the hgsl alias for one-line shortlog convenience
  * Added migration notification for rails plugin
  * Merge pull request #2249 from pabrahamsson/obsd_colorls
  * Merge pull request #2275 from wjv/wjv
  * Added/modified some useful aliases.
  * Add FreeBSD support for autojump plugin
  * Added Amuse zsh theme
  * wd.plugin: Added checks, readme and completion
  * wd.plugin: Fixed nested dirs
  * Merge pull request #2261 from webframp/feature/chruby-plugin
  * Merge pull request #2259 from eddiemonge/patch-1
  * Merge pull request #2266 from ssm/plugin/pyenv
  * Merge pull request #2271 from ashleyh/master
  * Merge pull request #2273 from thibaudgg/patch-1
  * Merge pull request #2276 from christianschmidt/master
  * Update _pass to follow symlinks for completion
  * Merge remote-tracking branch 'upstream/master'
  * Use precmd hook for updating OS X proxy icon
  * Update _heroku config arguments (Heroku Client v3)
  * Add update statistics
  * fix pip plugin
  * adding a check for git config option to disable git_prompt_info() on a per repo basis
  * unified and improved Rails plugin
  * Add pyenv plugin
  * Add simple plugin for chruby ruby version manager
  * Add support for sublime 3
  * standardize logic blocks
  * Merge pull request #2084 from mekanics/update-pod-plugin
  * Merge pull request #2253 from eddiemonge/patch-1
  * Merge pull request #2209 from quodlibetor/pip-caching-fixes
  * Merge pull request #2257 from mfaerevaag/master
  * Added wd plugin
  * Rebranded plugin according to Zypper's official alias
  * no tabs in a space-d file
  * basic command line xcode functionality
  * add aliases to readme
  * add new alias to zeus
  * Add support for colored ls output on OpenBSD
  * Merge pull request #2219 from Profpatsch/theme-agnoster
  * Merge pull request #2244 from marcoccchan/master
  * Merge pull request #2218 from wari/linuxonly-rename
  * Merge pull request #2239 from santagada/master
  * Merge pull request #2243 from sabarishcrri/bundle_plugin_nobundle_fix
  * Merge pull request #2245 from cadusk/p3
  * python3 clean updated.
  * getting the projects name correctly and making compdef to work with mux alias
  * Use environment specific open command when creating a new Jira issue.
  * bundle plugin throwing error when bundle is not in path while initializing
  * Fix issues with special characters when running mvn
  * agnoster theme not showing virtualenv status
  * Added the Bureau theme
  * Added nvm.zsh to detect current Node.js version
  * Modification to the frisk theme to work with the BZR lib
  * Modification to the frisk theme to work with the BZR lib
  * Prevent errors in prompts if no info available. Define empty functions instead of none at all if we can't figure out the platform.
  * Merge pull request #2220 from nishigori/fix-bad-ps-syntax
  * Fix bad ps syntax in ssh-agent plugin
  * Forgot one symbol for hg.
  * Merge pull request #1529 from aquaplanet/fix-sshagent-openbsd
  * `linuxonly` doesn't work unless renamed properly
  * Merge pull request #2174 from oxnz/master
  * randquote plugin correcting an issue about encoding some people was having added a message when the user doesn't have curl added varibles for colors->easier to customize
  * Make the pip cache work with djangopypi2
  * pip: successfully cache all the packages
  * Update git.plugin.zsh
  * updated to the latest version of cocoapods 0.27.1
  * themes plugin now picks a random theme if no argument is provided.
  * Add "options" as a valide 1st argument
  * Add configuration placeholders to installer template
  * Re-add whitespace
  * Add command blacklist support to bundler plugin
  * Minor gitignore fix.
  * Merge pull request #1688 from mbauhardt/z
  * Merge pull request #2138 from Profpatsch/theme-agnoster
  * Merge pull request #2165 from kevinxucs/custom-gitignore-fix
  * Merge pull request #1963 from shajra/pr/gpg-fix
  * Merge pull request #2078 from tbuehl/master
  * Merge pull request #2192 from kevintraver/tmux-aliases
  * Merge pull request #2184 from jmagnusson/agnoster_respect_venv_disable_prompt
  * Merge pull request #2107 from maxd/master
  * Add tmux aliases
  * Fix: Agnoster theme added venv name even if disabled See http://www.virtualenv.org/en/latest/index.html\?highlight\=virtual_env_disable_prompt\#activate-script for info regarding this.
  * Added the spectrum_bls function, which prints all 256 colors set as the background.
  * add itunes function to control itnues from the terminal
  * Add support .venv folder as virtual env
  * don't clobber existing RBENV_ROOT & follow Homebrew's default behavior
  * Moved misplaced plugins.
  * gitignore fix for custom folder.
  * removing a github redirect during install
  * Added a completion plugin for the new aws-cli tool
  * Merge pull request #2132 from jkaving/forklift2
  * Merge pull request #2139 from deiga/patch-1
  * Merge pull request #2145 from futjikato/master
  * Updated completion to work with comma seperated list
  * Added gitignore plugin ( for gitignore.io )
  * Added '.jar'
  * Added '.war' extension to unzip
  * More expressive symbols for git and mercurial.
  * Add support for ForkLift 2 to the ForkLift plugin
  * Fix work_in_progress in empty git repos
  * Check bundler version to avoid error with unsupported command line arguments
  * Revert "Replace no unicode glyph on hexa string"
  * Merge pull request #2065 from prudprud/master
  * Merge pull request #1763 from jonilicious/master
  * Merge pull request #1967 from tchaudhri/gdc_git_alias
  * Merge pull request #2079 from paulmelnikow/subl
  * Merge pull request #2077 from paulmelnikow/nvm
  * Merge pull request #2060 from dchusovitin/bug-node-doc
  * Merge pull request #2066 from agronemann/patch-1
  * Merge pull request #2087 from Stibbons/gsemet_push_theme_chooser
  * Merge pull request #2098 from monstermunchkin/master
  * Merge pull request #2043 from quodlibetor/fix-pip
  * Merge pull request #2053 from fluxrad/mosh
  * Merge pull request #2093 from zdevex/fixCommentsInTemplate
  * Merge pull request #2099 from mchaisse/master
  * Merge pull request #1840 from yleo77/master
  * Merge remote-tracking branch 'robbyrussell/master'
  * Added WIP alert to the gallois' theme
  * Added WIP (work in progress) feature to git.plugin
  * jump plugin: fix autocompletion with single mark
  * Added virtualenv plugin data to af-magic theme.
  * Fixed comments in zshrc.zsh-template about disabling auto updates.
  * Merge pull request #1987 from zvirusz/patch-1
  * Merge pull request #2002 from stibinator/master
  * Merge pull request #1829 from docwhat/compinit
  * Merge pull request #839 from eproxus/sunrise-fixes
  * Merge pull request #2080 from Mehonoshin/bundler-parallel-installing
  * Merge pull request #1975 from fff/master
  * repo list search one level deeper
  * Completion for python, pep8, autopep8 and pylint
  * Display right prompt in theme chooser
  * New aliases for repo plugin
  * typo
  * updated the arguments list to the newest version (0.24.0) of cocoapods
  * Logo draft 1...
  * Merge pull request #2045 from jeroenjanssens/master
  * Fix aliasing pwd
  * Mark function asks for confirmation and uses basename of directory when no argument is given
  * Change marks function and remove 'function' keyword as suggested by pielgrzym in https://github.com/robbyrussell/oh-my-zsh/pull/2045#issuecomment-22820224
  * Add _completemarks function as suggested by pielgrzym in https://github.com/robbyrussell/oh-my-zsh/pull/2045#issuecomment-22826540
  * Merge pull request #2 from JustinAiken/feature/marks_autocomplete_avaiable
  * Support of parallel bundle install
  * Better filename matching
  * Filter out missing links with jump autocomplete
  * Sublime Text: Harmonize alias with the Sublime Text install instructions
  * NVM: Avoid providing completions when nvm is not installed
  * Add commonly used git stash aliases
  * Plugin for Node Version Manager
  * Add completion for package add and remove
  * Add autocompletion plugin for meteor command
  * Update bundler.plugin.zsh
  * Replace no unicode glyph on hexa string
  * Merge remote-tracking branch 'robbyrussell/master'
  * Fixed opening documentation on Linux (node)
  * gitfast: update to upstream v1.8.4
  * Add support for mosh (remote-shell) tab completion.
  * Add tab completion for jump plugin
  * Add jump plugin, which allows you to easily jump around the file system
  * Improve pip plugin options support
  * changed duck to ddg for alias
  * Merge pull request #2028 from AeonAxan/master
  * Merge pull request #1672 from miry/rails3_command_fix
  * Merge pull request #1790 from simlegate/master
  * Merge pull request #1961 from brenttheisen/issue_1952_pr
  * Merge pull request #1960 from mekanics/plugin-pod
  * Add Pure theme
  * Merge branch 'master' of https://github.com/AeonAxan/oh-my-zsh
  * fixed minor errors
  * Update README.md
  * add docker autocomplete plugin
  * Updates Zhann theme
  * added duckduckgo to web-search
  * added duckduckgo to web-search
  * Added completion for second argument for 'brew reinstall'
  * Merge pull request #1988 from jwarwick/mix
  * Merge pull request #1992 from jeromemacias/patch-1
  * Merge pull request #1994 from kennethgeerts/master
  * Merge pull request #1993 from zvirusz/patch-2
  * Updated gem plugin zsh completion (gem 2.0.3).
  * In capistrano completion show also tasks without description
  * Fix symfony command completion 'permission denied'
  * Added autocompletion support for Elixir mix command
  * Added 'reinstall' command to brew completion
  * Merge pull request #1980 from awidegreen/upstream
  * Merge pull request #1981 from trobrock/knife-ssh
  * No cat, and hide errors for missing cache file
  * Add knife_ssh command to make connecting to servers managed with chef easier
  * Fix ssh-agent plugin identities comment for using multiple identities.
  * set default value `--max-count=10`
  * Merge remote-tracking branch 'robbyrussell/master'
  * PLUGIN: gpg-agent: export SSH_* environment variables too
  * show file liste on 'pod push [REPO]' and tab, 'pod spec lint' and 'pod podfile-info'
  * fixed typo in tmux plugin
  * Added a 'git diff --cached' alias -> 'gdc'
  * fix gpg-agent "running already" check
  * Copy and paste of two functions from Ubuntu 13.04's version of /usr/share/zsh/functions/Completion/Unix/_git that were referenced in 46f0d8d. Fixes #1952.
  * correct filename in the comments
  * Merge pull request #1935 from mateitrusca/master
  * supplemented with options
  * Update jonathan.zsh-theme
  * Add a plugin for systemadmin ops and developer
  * show repos on pod push
  * pod-list
  * commands and subcommands
  * first few lines for the autocompletion of cocoapods
  * Add sudo plugin
  * Update powify for displayed parameter is not enough, and when there is no directory error
  * Add version option
  * fixed typo in tmux plugin
  * Add shell built method
  * Add option for show in the command execution time stamp in the history
  * Modify determine the oh-my-zsh installed in non-default path of the installed
  * Update gem completion
  * Merge pull request #1764 from johnjohndoe/feature/rails3-autocompletion
  * Merge pull request #1920 from dongweiming/update-coffee
  * Merge pull request #1916 from okuramasafumi/master
  * Merge pull request #1919 from dongweiming/breaking-change-bower
  * Merge pull request #1917 from brandonblack/rvm-plugin
  * Update coffee completion
  * The current version of bower is completely unavailable, plugin depth modification
  * rvm plugin: update to ruby version helpers and rvm-update
  * Change duplicated alias name
  * Add autocompletion for Rails3.
  * Merge pull request #1913 from chriskrycho/patch-2
  * Add more capable hg incoming and outgoing count handling
  * Merge pull request #1859 from ayushs/plugin-git-clean
  * Merge pull request #1864 from Stibbons/gsemet_push_git_plugin
  * Merge pull request #1865 from Stibbons/gsemet_push_repo_plugin
  * Merge pull request #1867 from telser/master
  * Merge pull request #1869 from lucasuyezu/env_logs
  * Merge pull request #1868 from mlacorte/master
  * Merge pull request #1880 from posva/rand-quote
  * Merge pull request #1876 from chriskrycho/patch-1
  * Merge pull request #1881 from iammichiel/patch-1
  * Merge pull request #1886 from tresni/patch-5
  * Merge pull request #1901 from geecu/autocomplete_required
  * Merge pull request #1708 from tessi/extend_mercurial_plugin
  * Merge pull request #1773 from essembeh/master
  * Merge pull request #1903 from andschwa/tmux_iterm2
  * Merge pull request #1904 from oohlaf/gpg-agent-fix
  * Merge pull request #1908 from UncleBill/patch-1
  * Merge pull request #1909 from gonghao/master
  * Merge pull request #1910 from dongweiming/add-celery-completion
  * Add celery completion
  * add virtualenv prompt support for agnoster theme
  * git-pull add --rebase option
  * Typo
  * Prevent starting multiple gpg-agents
  * Not loading home tmux confs when iTerm2 tmux integration is enabled
  * Adding support for iTerm2 tmux integration via option '-CC'
  * Merge pull request #1872 from gdetrez/new-powerline-range
  * Merge pull request #1873 from charlesjohnson/bundler-plugin
  * Merge pull request #1887 from tgkokk/git-slow-fix
  * Merge pull request #1889 from jerolimov/patch-1
  * remove unused function
  * autocomplete required packages as second argumet
  * Merge pull request #1756 from rkj/master
  * Merge pull request #1885 from eakret/termsupport-fix
  * Merge pull request #1894 from codewhale/master
  * Merge pull request #1893 from jeremydt/postgres
  * debian plugin: ignore alias in sudo/aptitude check
  * Add new plugin for homebrew installed version of postgres
  * Do not clear tab when calling it with an argument.
  * Merge pull request #1877 from spazm/virtualenvwrapper-cleanup
  * Merge pull request #1878 from spazm/virtualenv-cleanup
  * Correctly detect Rapid Board
  * Fixed slow behavior when using GitHub wrappers
  * Better super-grep
  * Escape both % and $ in the command line
  * New plugin 'common-aliases' for optional cutting edge zsh aliases
  * source ~/.profile for upgrading (to source the proxy configuration)
  * Adding a rebase option to git alias.
  * Messed up the comment somehow...
  * Random quotes from the internet
  * virtualenv cleanup: replaces subshell with prompt expansion.
  * virtualenvwrapper plugin cleanup
  * Add count for incoming and outgoing changesets.
  * Merge pull request #1870 from mfrobben/patch-1
  * Update bundler.plugin.zsh
  * Update bundler.plugin.zsh
  * Update the character used in powerline
  * Update README.textile
  * add some alias for git flow
  * Adding testlog and prodlog.
  * Fixed color on git prompt for superjarin theme
  * A cabal plugin based on the lein plugin
  * Improvement in the git plugin
  * New plugin for git-repo (https://code.google.com/p/git-repo/)
  * Added alias for git clean
  * Merge pull request #1849 from lemieux/master
  * fix the open command in linux using xdg-open
  * Merge pull request #1834 from croach/disable_untracked_files_dirty_fix
  * Merge pull request #1775 from marcusmueller/fixupgradetool
  * add gf alias for git flow
  * Merge pull request #1837 from xuhdev/web-search
  * Merge pull request #1839 from Kronuz/patch-1
  * Fixed recursion. Git not needed for it to work.
  * Add web-search plugin.
  * Adding a fix for the DISABLE_UNTRACKED_FILES_DIRTY option.
  * Create the zcompdump based on version and host
  * add search by filename and file content feature
  * Merge pull request #1803 from bebugz/patch-1
  * gentoo linux support
  * add git alias 'gcmsg' and stand for 'git commit -m'
  * add git alias 'gcmsg' and stand for 'git commit -m'
  * rename gcm to gcmsg and stand for 'git commit -m' #1790
  * rename gcm to gcmsg and stand for 'git commit -m'
  * rm alias gcm='git checkout master' and add alias gcm='git commit -m'
  * Merge pull request #1774 from kevinxucs/sublime-default-2
  * Merge pull request #1779 from lorn/fasd_update
  * Cache for fasd --init
  * plugged_in function
  * eliminated unnecessary cd and failing substitution
  * Change sublime text path select priority on mac.
  * Uncomment l alias
  * Update the wrong variable used in rb20 function. Fixes #1762
  * Fixed missing retcode function
  * extend mercurial plugin to be more like git/svn
  * Merge pull request #690 from essembeh/master
  * Merge pull request #1254 from systemfreund/master
  * Spin to bundler
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Resolving conflict with merge of #1058
  * Merge pull request #1633 from alec-c4/master
  * Merge pull request #917 from agate/patch-1
  * Merge pull request #1091 from jmazzi/patch-1
  * Merge pull request #1102 from drnic/git-config
  * Merge pull request #1225 from bobmaerten/patch-1
  * Merge pull request #711 from jasongill/textmate-plugin-improvement
  * Merge pull request #424 from hackedy/fix
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Resolving conflict when merging in #528
  * Merge pull request #922 from sbfaulkner/master
  * Merge pull request #1053 from cwoodcox/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Updating the README file
  * Merge pull request #1088 from avit/avit-theme
  * Merge pull request #818 from jmacdonald/master
  * Merge pull request #1569 from ZeroKnight/master
  * Resolving conflict with merge of #970
  * Merge pull request #1223 from bigjust/master
  * Merge pull request #1620 from hreese/gpg-agent_with_sensible_ssh-agent
  * Merge pull request #1490 from khrt/master
  * Merge pull request #1565 from serdardalgic/autoenv-plugin
  * Resolving conflict in #1266 merge
  * Resolving conflict when merging in 1570
  * Merge pull request #1575 from mguindin/agnoster-change
  * Merge pull request #1582 from To1ne/pushdminus
  * Merge pull request #1608 from swanandp/m_lion_terminal_same_tab_support
  * Merge pull request #1622 from hacfi/patch-1
  * Merge pull request #1634 from Anahkiasen/patch-1
  * Merge pull request #1641 from NeuralSandwich/master
  * Merge pull request #1702 from mbauhardt/copyfile
  * Merge pull request #1715 from dbohdan/master
  * Merge pull request #1724 from miry/rails_aliases
  * Merge pull request #1703 from marcparadise/mp/knife-chef-11-initial-support
  * Merge pull request #1704 from laggyluke/st3
  * Merge pull request #1718 from toctan/master
  * Merge pull request #1721 from z2v/hgplugin
  * Merge pull request #1707 from bkg/django-static
  * Merge pull request #1714 from f0y/07738ea86330b7b77127fc6f18474b3da2c6ecec
  * Merge pull request #1719 from MatthR3D/master
  * Merge pull request #1726 from rkj/master
  * Merge pull request #1728 from szines/patch-1
  * Merge pull request #1729 from statschner/master
  * Merge pull request #1739 from felipec/fc/gitfast
  * Merge pull request #1749 from johnjohndoe/feature/zeus-auto-completion
  * Merge pull request #1733 from jaseg/patch-1
  * Merge pull request #1734 from cborgia/master
  * Merge pull request #1737 from hron84/feature-bundler-add-cleanup
  * Merge pull request #1738 from ronshapiro/master
  * Merge pull request #1748 from tobiassjosten/patch-1
  * Merge pull request #1740 from felipec/fc/git
  * Merge pull request #1750 from JamesFerguson/master
  * Only trim remote names; be git-flow friendly
  * Update rails4.plugin.zsh
  * Add auto-completion for zeus.
  * Added 'jekyll' to list of bundled commands
  * Merge pull request #1745 from jtheoof/master
  * Merge pull request #1747 from dhemmerling/mvn_tomcat-redeploy
  * mvn plugin was missing "redeploy" completion for tomcat.
  * Added option to allow untracked files as non dirty
  * gitfast: fix prompt
  * gitfast: synchronize with upstream
  * git: fix parse_git_dirty()
  * Separate the battery_pct_remaining data into it's own function so that it can be obtained even if the battery is connected.
  * Adding undocumented clean command to completion
  * Edited Grammar in template file
  * The safe-paste plugin now works with tmux, too
  * Added git-flow-avh plugin.
  * Update rvm.plugin.zsh to the latest ruby versions
  * Return code instead of dollar sign
  * Added global aliases to use RAILS_ENV.
  * Edit some yaourt aliases and add some
  * command-not-found support for Arch Linux
  * Implemented UTF-8 support in fishy.zsh-theme.
  * Add colorize plugin
  * Merge pull request #1526 from filipechagas/master
  * Merge pull request #1531 from lcosmin/master
  * Merge pull request #1532 from ryanneufeld/torrent_tools
  * Merge pull request #1537 from everbird/master
  * Merge pull request #1540 from goofansu/add-rebar-plugin
  * Merge pull request #1651 from deepusudhakar/master
  * Merge pull request #1696 from henryyan/master
  * Merge pull request #1700 from Bercio/master
  * Merge pull request #1701 from mbauhardt/copydir
  * Merge pull request #1706 from keyvez/master
  * Merge pull request #1711 from bertabus/master
  * Added Vundle clean to remove bundles removed from vimrc
  * Support for Sublime Text 3
  * Use completions with django-admin.py
  * Add collectstatic to django command completions
  * Escape spaces in folder name so script won't fail
  * Add alias for 'hg bookmarks'
  *  initial support for chef 11 integrated knife-essentials
  * a plugin (function) which copies the content of a file into the clipboard
  * a plugin (function) which copies the current directory into the clipboard
  * Merge pull request #1699 from Bercio/patch-1
  * Merge pull request #1689 from afh/pull/emoji_clock
  * >! doesn't work with no clobber, echo is redundant. Fixed all.
  * "$PWD" = "PWD", >! doesn't work, echo is redundant. Fixed all.
  * Add emoji-clock plugin
  * Merge pull request #1208 from jaischeema/master
  * Merge pull request #1060 from danielbayerlein/new-theme-inspired-by-peepcode
  * Merge pull request #729 from doitian/plugin_tmuxinator
  * 005d967dc4e879f304607a706ccd18886e630dc1
  * Merge pull request #1632 from jmatth/tmux_plugin
  * Merge pull request #1652 from z2v/master
  * Merge pull request #1654 from bertag/parse-git-dirty-support-for-1.6
  * Merge pull request #1655 from nubs/phing-and-cache-files
  * Merge pull request #1656 from hacfi/patch-2
  * Merge pull request #1665 from bmcorser/patch-1
  * Merge pull request #1679 from KokaKiwi/master
  * Merge pull request #1680 from zbrox/master
  * Merge pull request #1681 from akre54/add-bower
  * Merge pull request #1685 from justinclayton/patch-1
  * Merge pull request #1686 from timsly/hub-autocomplete
  * Merge pull request #1690 from docwhat/git-untracked
  * Merge pull request #1662 from rylwin/patch-1
  * Merge pull request #1674 from simeonwillbanks/master
  * Merge pull request #1678 from lesmyrmidons/symfony2
  * Merge pull request #1682 from maplebed/ben.knife
  * Merge pull request #1691 from gianu/master
  * Merge pull request #1697 from dsx/sublime-plugin-fix
  * Merge pull request #1698 from ConradIrwin/safe-paste
  * +safe-paste plugin
  * Prevents echo of _sublime_darwin_paths contents
  * Added $PATH to PATH in install shell
  * Removed colors from parenthesis.
  * New theme: Gianu Theme
  * This fixes checking for git untracked items
  * ohmyzsh plugin of the z project: https://github.com/rupa/z
  * added hub autocomplete instructions
  * Update _vagrant
  * use hostname instead of hostname -s
  * adding docs about knife path config variables
  * allowing you to override knife paths
  * fix some references from npm --> bower.
  * add bower autocompletion
  * Powify autocomplete
  * Add 'kiwi' theme
  * Add colored man plugin.
  * modify alias sfc => sf
  * Simplification name aliases and adding new alias
  * Fixes #1485 zeus should not be bundled
  * Mercurial: add alias for pull with rebasing
  * Merge pull request #749 from blueyed/setopt-correct
  * Merge pull request #1657 from ysmood/master
  * Merge pull request #1658 from kavu/patch-1
  * Merge pull request #1659 from AshleyS/master
  * Merge pull request #1661 from hellerbarde/master
  * Merge pull request #1558 from sbooob/master
  * Merge pull request #1573 from flz/master
  * Merge pull request #1595 from nevir/sublime3-support
  * Merge pull request #1598 from zasdfgbnm/master
  * Merge pull request #1607 from gekken/master
  * Merge pull request #1610 from mcaserta/scala_and_sbt_plugins
  * Merge pull request #1611 from ripdog/patch-1
  * Merge pull request #1614 from miklos-martin/bower
  * Merge pull request #1616 from sxeraverx/master
  * Merge pull request #1524 from bonifaido/master
  * Merge pull request #1638 from RomainBelorgey/master
  * Merge pull request #1650 from ishtu/master
  * Merge pull request #1663 from flavius/master
  * Merge pull request #1664 from marcel-wolf/master
  * Merge pull request #1668 from sheerun/patch-1
  * Merge pull request #1669 from desimone/master
  * Merge pull request #1671 from lifinsky/master
  * Exporting path to fixed config as a global variable.
  * Prefixing tmux wrapper function with '_'.
  * IMPROVED: untracked file status has priority over modified (ie: if you have both modified and untracked files, your prompt will be red indicating the presence of untracked files)
  * Use new style of rails command.
  * Fix grails plugin
  * Added golang completion support from golang.org
  * Use --no-rehash option for faster startup
  * Alias for commit and commit all with amend
  * add ssh-agent option to set default lifetime of identities
  * allow setting a custom HISTFILE before oh-my-zsh is loaded
  * Fix whitespace
  * last-working-dir: Use >! to overwrite $cache_file
  * fix git_prompt_status() to not say the repository has untracked files all the time
  * Modified to use full parameter as newer versions of base64 uses lowercase D
  * Fix git dirty status in dallas.zsh-theme
  * opt: Optimize the color scheme. Add some basic comments.
  * Autocomplete composer default methods if composer.json is not available
  * Allow ":" and "-" characters in phing tasks.
  * Use [ -nt ] instead of stat -f%m to check cache files.
  * Merge remote-tracking branch 'upstream/master'
  * add: A new theme 'ys'.
  * Tweaked parse_git_dirty() in lib/git.zsh to support proper dirty/clean parsing against both git 1.6 and git 1.7+
  * Mercurial: add aliases for 'incoming' and 'outgoing' commands
  * Escape /Users/desudhak/.oh-my-zsh path (previously broke spaces in path)
  * add function vncviwer
  * Merge pull request #1645 from mbologna/master
  * added comment for auto-generated hostname color
  * added michelebologna theme
  * Updated battery plugin.  Displays charging time.
  * Update _capistrano
  * Add alias for "composer dump-autoload"
  * Added rails4 plugin
  * Checking to make sure tmux is actually installed before running plugin.
  * Adding options to choose tmux TERM for 256 and non-256 color terminals.
  * Adding compdef to maintain tmux completions.
  * Fixing typo in alias.
  * Adding option to prevent autostarting tmux more than once in the same session.
  * Checking if already in tmux before autostarting in tmux in tmux plugin.
  * Checking environment instead of local variable for fixing term in tmux plugin.
  * Fixing typos, logic, and gremlins in tmux plugin.
  * Adding helper tmux config files to tmux plugin.
  * Enabling autostart of tmux in tmux plugin.
  * Adding comments to tmux plugin.
  * Tmux plugin now just runs tmux if any extra args are given.
  * Now checking for 256 color terminal in tmux plugin.
  * Adding main function and alias to tmux plugin.
  * Starting tmux plugin with basic config variables.
  * Fix Symfony2 command completion 'permission denied'
  * Added --quiet to suppress message about gpg-agent already running.
  * Disable ssh-agent support if another ssh-agent is already running.
  * pipe git version check error to /dev/null (for when git doesn't exist)
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Update plugins/extract/extract.plugin.zsh
  * SBT and Scala plugins.
  * Support for opening tabs and windows in the same This fixed #1498 for me on Mountain Lion
  * Update plugins/rvm/rvm.plugin.zsh
  * Did a full circle and went back to # On branch master # Changes to be committed: #   (use "git reset HEAD <file>..." to unstage) # #	modified:   git.zsh #, ignoring untracked files, which seems to be the primary cause for slowness
  * Fixed dirty check to include files added to index
  * new plugin: start fbterm automatically in /dev/tty*
  * Merge remote-tracking branch 'upstream/master'
  * Merge pull request #1594 from jbhannah/rbenv-gems-fix
  * Merge pull request #1583 from To1ne/pj.plugin
  * Support for Sublime Text 3, with fallback
  * Fix rbenv gems helper
  * Merge remote-tracking branch 'upstream/master'
  * Merge pull request #1586 from HeroicEric/master
  * add alias for rspec to zeus plugin
  * added pj.plugin
  * use pushdminus
  * [agnoster] modifying theme to show dot for dirty files and plus for staged files in git repos
  * updated adben theme: added offline content, subversion support, refactored prompt
  * Add new profiles plugin.
  * Closer to original status command, using SUBMODULE SYNTAX
  * Better custom theme loading
  * Faster dirty git status check (using git diff)
  * Add autoenv plugin, which adopts using Kenneth Reitz's autoenv into oh-my-zsh.
  * ADDED: Mercurial prompt info support even if hg prompt extension is unavailable
  * ADDED: Mercurial repository info
  * Adding MIT-LICENSE Closes #655
  * Merge pull request #1534 from gberenfield/master
  * Merge pull request #941 from dcreager/configurable-blinks-theme
  * Merge pull request #1077 from Mezzle/add-option-to-show-git-status
  * Merge pull request #1054 from ptillemans/master
  * Merge pull request #1164 from fuksito/master
  * Merge pull request #837 from stacksmashing/master
  * Update to a better fab compeletion script.
  * Add rebar to plugin
  * Merge remote-tracking branch 'upstream/master'
  * Add new plugin to autocomplete fabric commands
  * Fixed coding style
  * moved bower plugin to a separate branch
  * cleaned up
  * Fix the fix for Issue #1479
  * fix for Issue 1479
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Adding torrent tools plugin.
  * Merge pull request #1510 from agnoster/agnoster-classic
  * Merge pull request #1517 from thisiskun/master
  * Fixes #1489
  * Fixed issue with NetBSD's ls
  * added support for subversion 1.7 for svn plugin
  * OpenBSD doesn't have -ef flags for ps. Both linux and OpenBSD have -x flags which works just as greate here
  * added crcandy theme
  * Fix gitfast problem for untracket files
  * Maven plugin completion fix for other (than Java) JVM languages
  * add symbol in darcs repos to match git and mercurial
  * add unbundled command
  * Revert "agnoster theme shows error code instead of an "x""
  * git lol
  * more catspeak
  * Added `verisions` option for `homebrew` completion
  * Merge pull request #1473 from bsteuber/fix-git-flow-feature-completion
  * Merge pull request #1475 from westonplatter/master
  * Merge pull request #1477 from madsgraphics/git_prompt_showstashstate
  * Add Stash toogle to display if there's some stash or not in `git_prompt_status`
  * fixes #1474 add zeus to bundle exec listx
  * use feature names instead of failing branch names in "git flow feature"
  * Merge pull request #1084 from avit/bwana-plugin
  * Merge pull request #1133 from mappleconfusers/605ad8725b06cc15f8523404f59060b6a71bb7a2
  * Merge pull request #1139 from mappleconfusers/pull_req_git
  * Merge pull request #1233 from mugenken/knife-check-cwd
  * Merge pull request #1467 from timothyandrew/patch-1
  * Merge pull request #1468 from larrylv/unset-config-file-variable
  * Unset `config_file` variable in oh-my-zsh.sh
  * Added a `migrate` alias.
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Merge pull request #1248 from grahamc/add-symfony
  * Merge pull request #1258 from caio/git-branch-status
  * Merge pull request #778 from rschmukler/plugin-osx
  * Merge pull request #794 from markdrago/cloud_parameter
  * Merge pull request #875 from ttddyy/prompt_git-remove
  * Merge pull request #880 from darrenclark/fix-mac-terminal-app-echo-issue
  * Merge pull request #1181 from paulmars/master
  * Merge pull request #1189 from petemounce/yum-quote
  * Merge pull request #1186 from r-darwish/history
  * Merge pull request #1247 from drnic/git-cmds
  * Merge pull request #1273 from ystein/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Resolving conflict in merge of #1313
  * Merge pull request #1387 from jimhester/vi-mode-patch
  * Merge pull request #1458 from ranman/master
  * Merge pull request #1454 from gAmUssA/patch-4
  * Merge pull request #1462 from aliasbind/master
  * Merge pull request #1460 from tresni/patch-4
  * Merge pull request #1459 from tresni/patch-3
  * Merge pull request #1463 from syphar/fix_last_working_dir
  * Fix prompt color: Change it back to green
  * plugin last-working-dir: create cache-directory if it doesn't exist
  * Print last exit status in mortalscumbag prompt
  * urltools for Everyone
  * Backwards Compatible Jira URLs #1378
  * use lazy load for virtualenvwrapper
  * hg_current_branch added to mercurial plugin
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Merge pull request #1457 from NeuralSandwich/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Fixing conflict in install scripts
  * Merge pull request #1328 from mfoo/master
  * Merge pull request #1301 from bencao/master
  * Merge pull request #1293 from cenkalti/master
  * Merge pull request #1295 from XL64/master
  * Merge pull request #1298 from nickhutchinson/fishy
  * Merge pull request #1382 from fushunpoon/master
  * Merge pull request #1191 from r-darwish/themes-plugin
  * Merge pull request #1235 from henryyan/master
  * Merge pull request #1241 from agrimaldi/git-extras
  * Merge pull request #1249 from korjavin/aptitude
  * Merge pull request #1255 from SuprDewd/master
  * Merge pull request #1256 from seegno/master
  * Merge pull request #1259 from bwl/sublime-fix
  * Merge pull request #1263 from tedv/headless-git
  * Merge pull request #1265 from aletessier/ssh-completion
  * Merge pull request #1274 from sc68cal/feature/git_decorate_log
  * Merge pull request #1277 from waveface/master
  * Merge pull request #1278 from bitboxer/forklift
  * Fixed Kernel Detection in battery plugin
  * Merge pull request #1284 from obmarg/feature/debianwhichfix
  * Merge pull request #1317 from thcipriani/junkfood_theme
  * Merge pull request #1319 from skatkov/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * resolving conflict in termsupport plugin
  * Merge pull request #1336 from aelesbao/plugin-systemd
  * Merge pull request #1341 from markusscherer/master
  * Merge pull request #1354 from F30/master
  * Merge pull request #1353 from a-b/master
  * Merge pull request #1371 from rdrey/master
  * Merge pull request #1376 from javageek/master
  * Merge pull request #1375 from dsx/better-pyclean
  * Merge pull request #1378 from hjhart/master
  * Merge pull request #1453 from simonoff/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * git find
  * Merge pull request #431 from meh/rsync-plugin
  * Merge pull request #409 from Bregor/patch-1
  * Merge pull request #214 from allancaffee/master
  * Merge pull request #1455 from NeuralSandwich/master
  * Merge pull request #1456 from sputnikus/master
  * Removing mcd as it conflicts with mtools
  * Renaming cap to capistrano
  * Functions for managing pacman-key
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Added Candy-Kingdom theme
  * Merge pull request #256 from lorrin/no-op_command-not-found
  * Merge pull request #253 from loopj/master
  * Added support for Mac to battery plugin
  * Update plugins/sublime/sublime.plugin.zsh
  * Merge pull request #516 from adben/master
  * Set default for rvm prompt prefix/suffix
  * Fix RVM loading and RVM ruby version info
  * Simonoff theme
  * Merge pull request #455 from aslamnd/master
  * Merge pull request #448 from n0nick/patch-1
  * Merge pull request #1451 from rmcastil/modify_readme_to_clarify_the_manual_way
  * Merge pull request #1452 from miry/github
  * Fix repo for github.
  * Make the NOTE an optional for improved instructions
  * Improve formatting of step 2 for clarity
  * Merge pull request #1393 from agate/patch-2
  * Merge pull request #1365 from pcasaretto/add-heroku-remote-switch
  * Merge pull request #1366 from op/last-working-dir
  * Merge pull request #1370 from ericmathison/syntax-fix
  * Merge pull request #1347 from paulredmond/plugin/jira
  * Merge pull request #1386 from sanbor/master
  * Merge pull request #1390 from pluton8/bugfix/autojump21
  * Merge pull request #1435 from Drarok/fix-svn
  * Merge pull request #1421 from cristim/master
  * Merge pull request #1399 from tresni/patch-1
  * Merge pull request #1400 from tresni/patch-2
  * Merge pull request #1416 from talmuth/master
  * Merge pull request #1410 from jimhester/per-directory-history
  * Merge pull request #1411 from niceview/rvm
  * Merge pull request #1413 from arnihermann/master
  * Merge pull request #1412 from jdavis/coffee_plugin
  * Merge pull request #1418 from Mehonoshin/patch-2
  * Merge pull request #1419 from ssrihari/master
  * Merge pull request #1439 from maxbane/master
  * Merge pull request #1442 from willman500/git-hub-flow-plugin
  * Merge pull request #1445 from knxroot/master
  * Modifying documentation in zshrc template for new config option
  * Merge pull request #1430 from danielsoneg/egd-update_frequency
  * Merge pull request #1437 from Partyschaum/master
  * Merge pull request #1446 from suzaku/patch-1
  * fix typo
  * Node.js version of urltools es more fast (53% aprox), you can try this with strace -o trace -c -Ttt
  * Add autocomplete for git "hubflow"
  * fixed autojump: autocompletion works with homebrew again
  * Merge branch 'master' of github.com:Partyschaum/oh-my-zsh
  * fixed autojump plugin: works with homebrew again now
  * Revert "Fix to restore bindings after switching to vi-mode"
  * fixed symbolic-ref git view of agnoster theme
  * removed 'x' from prompt_context() function name
  * Fix the backwards svn status, and add comments explaining which way grep does things.
  * Whitespace cleanup.
  * Add UPDATE_ZSH_DAYS setting
  * Merge pull request #1426 from caarlos0/master
  * fixes my wrong commit - fixes #1423
  * Merge pull request #1391 from logicmd/master
  * Merge pull request #1388 from fuadsaud/agnoster_theme_show_exit_status
  * Merge pull request #1395 from caarlos0/master
  * Merge pull request #1406 from chinghanho/master
  * Merge pull request #1404 from Bklyn/master
  * Merge pull request #1396 from webframp/fix/brew-autojump-zsh
  * Merge pull request #1415 from jmatth/git_root_pull
  * Merge pull request #1417 from felipec/fc-git-upstream
  * Added a small mod of the tjkirch theme
  * Added alias to rake db:test:prepare
  * Added gwc(git whatchanged alias)
  * Add gifast plugin
  * e alias
  * fixing various issues with build, add runinstall option
  * fixing some build issues...
  * Add support of screen-* $TERM in screen plugin
  * fixing issue with solr in jboss start
  * go
  * param -i para gerar installer
  * oops
  * totvs utils
  * Adding grt alias to the git plugin.
  * Use pull --rebase for 'gup' shortcut.
  * Added host to prompt
  * Added sf Symfony2 binary alias
  * Added a CoffeeScript plugin.
  * Use rvm completion from ~/.rvm/scripts/zsh/Completion
  * Replace reset-prompt with push-line and accept-line
  * Improved statistics functions, effect:
  * Untabify
  * Handle metachars in svn status output using grep -q
  * Fix /bin/sh compatibility issue in install.sh
  * Update plugins/svn/svn.plugin.zsh
  * Update themes/minimal.zsh-theme
  * made dpkg -i more util
  * update autojump plugin for latest brew installed autojump
  * mvn.colors.plugin.zsh was not read... mergin with mvn.plugin.zsh.
  * Added some maven love.
  * Update plugins/git-flow/git-flow.plugin.zsh
  * Update plugins/sublime/sublime.plugin.zsh
  * Fix sourcing brew's autojump of version 21.0.3+
  * agnoster theme shows error code instead of an "x"
  * Fixes for vi-mode terminal overwriting bugs
  * Added pass plugin in order to provide completion.
  * Expand for-loop so that it works under Snow Leopard Terminal.app.
  * Update plugins/jira/jira.plugin.zsh
  * Updated code from answer URL
  * Added ability to specify list of directories for pyclean to override default current directory
  * Fixed node-docs
  * Fix color syntax
  * Added last working directory plugin
  * Add the heroku --remote switch
  * Replace hardcoded key escape sequeneces with dynamic ones from terminfo.
  * add git-extras plugin
  * Merge remote-tracking branch 'upstream/master'
  * Make sure the terminal is always in application mode when zle is active.
  * Don't clobber standard Esc+. behavior
  * forgot to save before committing. doh
  * Added documentation to key bindings.
  * Set the '-R' option for less not in $PAGER, but as $LESS.
  * updated symbol
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Something to be said for symmetry
  * spacing makes me something
  * parens tweak
  * removed weird characters
  * moved spacing
  * Wrong URL :zap:
  * Merge pull request #1344 from danielcsgomes/master
  * Merge pull request #1306 from josh-/master
  * Merge pull request #1312 from koenpunt/fixes_cap_plugin
  * Merge pull request #1330 from trobrock/hide-rvm-prompt
  * Merge pull request #1333 from b4mboo/master
  * Merge pull request #1335 from paulredmond/plugin/jira
  * Merge pull request #1346 from ianchesal/urltools
  * make README reflect latest changes
  * URL Tools Plugin
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * added a comment to the composer installation alias
  * added Composer completition and aliases
  * added two aliases to Symfony2 Plugin
  * fix title setting bug in xterm and urxvt
  * fix test aliases
  * Missing comment line
  * Added systemd plugin with aliases for systemctl commands.
  * look for test/unit instead of test/units. #typo
  * Correct error message.
  * Merge pull request #1327 from agnoster/master
  * Clean up doc
  * Jira ticket shortcut to browse existing issues or create a new issue.
  * Merge remote-tracking branch 'upstream/master'
  * Add zeus plugin
  * Make rvm prompt function a bit cleaner
  * Fixing the rvm_prompt_info command, now it will not show empty parens if no rvm is currently being used
  * Add user-local installation autojump zsh plugin source
  * Add link to gist
  * Updated documentation for agnoster theme
  * Merge pull request #1318 from trobrock/add-puma-to-bundler
  * Merge pull request #1320 from jimhester/vi-mode-patch
  * Merge pull request #1321 from jimhester/per-directory-history
  * Merge pull request #1322 from jimhester/colemak
  * Merge pull request #1323 from lxmonk/autojump-port
  * Use HISTFILE evironment variable directly rather than copying it
  * added autojump plugin support for mac os x + port
  * Red prompt for remote hosts
  * Colemak plugin
  * Per directory history plugin
  * Fix to restore bindings after switching to vi-mode
  * Last spacing adjustment...I swear
  * Modified spacing one last time
  * Replace cp verbose with rsync
  * Bundle exec puma also http://puma.io
  * modified spacing on junkfood theme
  * Added fat arrow the theme
  * Refactored theme
  * Added space to prompt
  * Added junkfood theme
  * git plugin: Add `gpoat` alias
  * Add agnoster.zsh-theme
  * fixed incorrect if/else
  * updated cap plugin to use `cap -T` instead of `cap show_tasks` which didn't exist (sometimes?)
  * Merge remote-tracking branch 'upstream/master'
  * fixed nginx vhost template, made variables local, imroved parameter validation
  * Merge remote-tracking branch 'upstream/master'
  * added lesscss plugin
  * Add new 'nanoc' plugin
  * Nuke _cap_does_task_list_need_generating
  * Rendering the 'vagrant box (remove|repackage)' completion code independant of Vagrant implementation details.
  * fix rvm auto complete, pointing to $rvm_path
  * nginx and php-fpm plugins
  * Update fishy theme to collapse working directory in PROMPT.
  * Merge pull request #1228 from clutt0n/master
  * Merge pull request #1287 from johnhamelink/master
  * Merge pull request #1279 from 3den/master
  * Merge pull request #1297 from everbird/master
  * add new plugin to autocomplete supervisor commands
  * Add empty function rbenv_prompt_info() if doesn't exists
  * search virtualenvwrapper.sh in PATH
  * Added another path for virtualenvwrapper plugin
  * Add keep branch option.
  * Added laravel plugin which gives aliases to artisan and bob, and provides autocompletion for artisan.
  * Debian plugin now pipes which stderr to stdout
  * new 3den theme with RVM and GIT
  * Merge branch 'master' of github.com:ptillemans/oh-my-zsh
  * new forklift plugin
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Add shortcut for showing log of all branches
  * fix typo in cd-wrapper
  * application completion
  * library completion
  * in hindsight, this is probably a bad idea
  * Correct variable used for global ssh known host completion
  * Make git use sha when branch name is missing.
  * completion of targets
  * instance and cluster completion
  * Add branch status support to git_prompt_status
  * Adding logic for ~/Applications folder installs of Sublime Text 2
  * Add a configuration option to disable autocorrect
  * Added a "please" alias for sudo
  * Merge branch 'master', remote-tracking branch 'rr/master'
  * Added go completion script. Taken from /misc/zsh/go
  * alias at=aptitude broke /usr/bin/at scheduler. Just an idea: change it to ap
  * Merge
  * node completion
  * delete os specific disable-patterns
  * help command, node completion
  * Adding a symfony plugin, for symfony 1
  * improvement: define PROMPT_HOST once on startup
  * added 'gcl'for 'git config --list'; and gd for 'git diff'
  * Merge pull request #1229 from seban/run_rails_without_bundle_exec
  * auto-upadate feature will now reset the epoch so that if a user doesn't say yes, it won't ask them again for a while. fixes #1240
  * Fix changelog --list completion bug
  * Added credits
  * Added git-extras completion
  * Added avit theme
  * Bwana plugin for reading man pages in Safari
  * add maven zsh autocomplete plugin, copy from juvenxu's bash maven autocomplete plugin
  * check for knife.rb in cwd
  * merge from upstream master
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * modify themes/jnrowe.zsh-theme, add host directive "Ξ (mbsd) ~ →"
  * 'rails' command should not be run with bundle exec
  * added _files values for certain options
  * completion options
  * added alias
  * added completions for all known arguments to all known commands
  * vagrant uses 'ssh-config' command, not 'ssh_config'
  * Add very basic virtualenv plugin
  * Merge pull request #1200 from andyfleming/master
  * apparently, this file must exist for the plugin to load
  * added completion for all asadmin subcommands
  * Merge pull request #1206 from Eustachy/upstream
  * Merge pull request #1216 from joshvermaire/patch-1
  * utilize sublime's embedded command line binary
  * escape whitespace
  * Merge pull request #1122 from varunkvv/master
  * Merge pull request #1127 from a-b/master
  * Merge pull request #1193 from bameda/master
  * Merge pull request #1209 from lwe/rbfu-plugin
  * Merge pull request #1170 from dipth/master
  * provide plugin for rbfu the ruby version switcher
  * Fix the rvm gemset right prompt:wq
  * Add new theme : jaischeema
  * Remove bogus "-" from nomz="ps -aux" alias.
  * Remove debug info
  * Dynamicly generate completion functions to support changing apt_pref
  * Add myself to the authors list
  * Use a static apt-get where only apt-get works
  * Add completion instructions for apt/aptitude commands
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of github.com:essembeh/oh-my-zsh
  * Comment l alias
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Merge remote-tracking branch 'upstream/master'
  * Added another path
  * Merge pull request #1190 from vpacher/master
  * Merge pull request #1192 from rcakirerk/a39c9ffe5b7236b6e4dc78efa80b478cc411af7f
  * Fix finding git issue. http://stackoverflow.com/questions/592620/check-if-a-program-exists-from-a-bash-script
  * Added completion to the theme selection plugin
  * Added themes plugin
  * added jexec
  * added plugin for jruby
  * Fix mismatched quote in yum plugin
  * Merge pull request #1174 from insside/rbenv-homebrew-fix
  * Merge pull request #1126 from natsumesou/fix-ignore-symlink
  * Merge pull request #1182 from jugyo/patch-1
  * Merge pull request #1159 from kristi/master
  * Merge pull request #1173 from walkah/virtualenvwrapper-osx-fix
  * Merge pull request #1168 from r-darwish/yum-plugin-fix
  * Added history plugin
  * correct the ruby version label for rbenv
  * add git remote branch autocomplete
  * theme cleanup
  * added first version of my theme af-magic
  * sanitized code according to coding style
  * rbenv plugin now uses 'brew --prefix rbenv' command to find rbenv folder
  * remove readlink call and clean up
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Explicitly tell rbenv to use zsh
  * Fixed unmached " in yum plugin
  * More usable and shorter aliases
  * avoid VCS folders
  * Merge pull request #977 from scialex/better-d
  * Merge pull request #980 from vmalloc/dircycle_plugin
  * Merge pull request #984 from vmalloc/less_r_pager
  * Merge pull request #985 from pomaxa/master
  * Merge pull request #999 from ChaosData/master
  * Merge pull request #1016 from fuksito/master
  * Merge pull request #1032 from r-darwish/suse
  * Merge pull request #1055 from daniellockard/patch-1
  * Merge pull request #1065 from ntpeters/patch-1
  * add --directory flag
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Updating README to ask people to stop sending themes for now
  * Merge pull request #1148 from erichmenge/git-flow-plugin
  * Merge pull request #1019 from matschaffer/patch-1
  * Use grep to detect if untracked files exist instead of storing all the output of ls-files.
  * Merge pull request #239 from fred-o/master
  * Merge pull request #1146 from westonplatter/master
  * Merge pull request #1152 from mispy/virtualenvwrapper
  * Merge pull request #1155 from s3dev/s3dev
  * Merge pull request #1145 from tjl2/master
  * Merge pull request #1156 from thackoun/master
  * fix a very minor bug with colors of parenthesis in the terminalparty theme
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Change hardcoded ~/.oh-my-zsh to $ZSH.
  * Plugin which loads Python virtualenvwrapper and activates virtualenvs on cd into git repos
  * Merge branch 'master' of github.com:westonplatter/oh-my-zsh
  * checking if airport allows git protocol
  * Merge remote branch 'upstream/master'
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Added spin to bundled_commands (Bundler plugin)
  * Add a couple of options for git-flow.
  * rails3, added rgm = 'rails generate migration'
  * Removing ey command from bundled_commands. It is not usually bundled.
  * Merge pull request #1138 from amarraja/master
  * Merge pull request #1140 from mappleconfusers/pull_req_debian
  * Now with 50% less auto-updates.
  * Add command to directly install the output of acs
  * Make the $apt_pref variable evaluatet at alias expansion by using single-quotes instad of double quotes
  * Add aliases for git-remote: gr...
  * Prevent the heroku command from being automatically bundle-exec'ed The heroku command should not be executed via bundler, see: https://github.com/heroku/heroku/issues/173
  * Enhance handleing of spaces in filenames
  * Add the fastfile plugin
  * Make (s)xf not search in current dir
  * Make grep recoursive
  * Enhance file find
  * Add Man
  * Add file finders
  * Enhance writing routines
  * env_defaul=>env_default
  * Add sudo without xargs shortcuts
  * Add pager shortcuts
  * Add download shortcuts
  * Add a description
  * Add cat (+write, +append), enhance formatting
  * Add the singlechar plugin
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Add helper to easily define default values for variables and env variables.
  * Add helper to get the value of an alias only
  * Fixed a bug in checking the platform
  * fino-time theme
  * add fasd plugin
  * Load symlink custom files
  * Add Sublime Text 2 alias for Linux.
  * Added zp and zps aliases for the SUSE plugin
  * Added suse plugins
  * Merge pull request #1026 from dir01/patch-1
  * Merge pull request #1079 from dylnhdsn/feature/sublime_text_plugin
  * Merge pull request #1105 from Drarok/fix-svn
  * Merge pull request #1111 from jimeh/fix-ZSH_CUSTOM-variable
  * Move example plugin to the custom plugins dir.
  * Load themes from `$ZSH_CUSTOM` instead of `$ZSH/custom`
  * Suppress "zsh: no matches found" error when $ZSH_CUSTOM has no files
  * Don't drop everything after a trailing slash, as this breaks standard svn branches: ^/branches/featurename ^/releases/Release-vx.y ^/trunk
  * added 'gcl'for 'git config --list'; and gd for 'git diff'
  * Fix formatting
  * Add instructions on handling updates and prompts.
  * changed the alias to use to cli provided by sublime text
  * added aliases for sublime text
  * Add option to disable status notification
  * Merge remote branch 'upstream/master'
  * Added yum aliases for: makecache, grouplist, groupinstall, and groupremove.
  * Add Theme "itchy"
  * Adds glo; glp (arg)
  * Added an if-statement to see if git is installed
  * Added subcommands for leiningen 1.7.0
  * command to restart pow process
  * small changes to make it prettier
  * add the half-life theme based on steeef and lambda
  * Added an <esc> to the begining of everything. I ran something when I was in insert mode once and all it did was shove !args... into the buffer.  <esc> first.
  * Updated the README to include documentation on the postCallVim callout
  * Added an optional callout to the end of the interaction function. I put it in to allow me to put the window focus on MacVim / GVim depending on the different OS I happen to be on
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * [themes/josh] Use $(current_branch) in prompt
  * add maven plugin
  * Python plugin: added pygrep command, simplified pyclean
  * Fixed: If you callvim on a non-existant file with a relative path, the CWD of the running gvim process is used, and that's not right.  We use the PWD explicitly instead, in this case
  * A plugin that makes it easier to interact with the (single) running instance of gvim
  * Add a cat smilie as alias for cat
  * Don't clobber standard Esc+. behavior
  * Plugin for encoding strings into base64 and decoding them
  * added powed command to list pow urls
  * delete time filed
  * Disabled title function for emacs term mode
  * fix gnzh theme to detect local rvm installations
  * change color of @ to cyan
  * add hostname behind username, example: henryyan [02:07:20]  ~/.oh-my-zsh git:(master) ✗
  * move kafeitu.zsh-theme to themes folder
  * Added kafeitu theme it modified by robbyrussell
  * Added link to wiki page for plugins to README.
  * current repository action
  * Pager is 'less -R' to support colored outputs
  * Add dircycle plugin: enables cycling through the directory stack
  * made the 'd' alias only show the directories that can be cd'ed to using the number aliases
  * Add gem build autocompletion
  * clean up rbenv support for 'fino' theme
  * merge changes from offical repo
  * Fix spurious correction with sudo vim
  * Add completion for pip install -r - so that it autocompletes requirements filenames
  * Merge pull request #958 from cruser42/master
  * Fixed bug introduced when fixing issue 896
  * Merge pull request #868 from wgriffioen/bundler_add_rails
  * Merge pull request #925 from cruser42/bugfix/gitversionfix
  * [JM] Removed LSCOLOR Declaration for Wider Support
  * Added New Theme: sonicradish  (256 colors)
  * Added a peepcode theme
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * change the color of arrow when the command line return an error
  * blinks theme works with light and dark Solarized
  * handle case where ~/.rvm/bin/rvm-prompt is not in path, so "which" can't find it
  * fixed introduced to parse_git_dirty
  * changed variable PRE_1_7_2_GIT to POST_1_7_2_GIT to make it more accurate
  * fixed asterisk display for modified repos in git prior to 1.7.2
  * add default rbenv_prompt_info implementation to close #878
  * added "publish" and "track" command completion for git-flow plugin
  * Fixed Mac OS X Terminal.app related issue with extra newlines being printed out sometimes
  * Merge pull request #666 from szetobo/rails_runner
  * Removed trailing spaces in Git files. Fixes #867
  * update rails runner alias to ru
  * prompt git-remove as deleted
  * added rails to bundled_commands
  * Merge pull request #663 from gravof/patch-1
  * Merge pull request #850 from johnantoni/pow-fix
  * Merge pull request #860 from sbfaulkner/rbenv-support-for-themes
  * Merge pull request #865 from iltempo/patch-1
  * adding engine yard command (ey) to bundler binstubs
  * adding rbenv support to all the rvm themes
  * Merge pull request #845 from tjwallace/bundler_plugin_fix
  * Merge pull request #717 from blueyed/github-plugin-working-hub
  * Merge pull request #801 from kalos/autojump
  * Merge pull request #811 from markdrago/remove_verbose_mercurial_flags
  * Merge pull request #853 from lepht/master
  * Merge pull request #810 from cseeger/master
  * Merge pull request #856 from sgharms/patch-1
  * Merge pull request #858 from tatey/bundle_plugin_middleman
  * Add middleman to bundled commands
  * Grammar update
  * Fixed compdef alias to use 'gd' as shortcut.
  * Updated to latest version of taskwarrior completions (using Taskwarrior 2.0b4)
  * bug : stop creating those ~ directories add powit command to symlink an app if it hasn't been already
  * don't check for tmp dir
  * add alias to view the standard out (puts) from any pow app
  * take in csexton's changes
  * fix for pow plugin to default to current dir
  * Merge pull request #721 from gawel/master
  * Merge pull request #783 from oteyatosys/master
  * Merge pull request #830 from dbye/speedup
  * Merge pull request #847 from msharp/master
  * added a rake plugin to disable zsh file globbing when calling rake tasks with square brackets
  * fix bundler plugin for root level folders
  * Merge pull request #840 from arbovm/master
  * Merge pull request #838 from Bounga/bundled_thor
  * Merge pull request #833 from backspace/patch-1
  * fixing #812: adding plugins w/o plugin.zsh file to fpath.
  * Correct color and font issues on Ubuntu
  * Add Thor to bundled commands
  * Removed the assignments to fpath as well, since that's all handled in the .oh-my-zsh/oh-my-zsh.sh boot script.
  * sprunge-plugin: Remove the unnecessary while loop.
  * Fix the behaviour of the sprunge plugin so that is preserves whitespaces and tabs.
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Don’t report that Oh My Zsh has been updated when it hasn’t.
  * Removed calls to compinit in the extract and the bundler plugins. compinit should only be called once, after all modules, libs, etc are imported.
  * Merge branch 'master' into cloud_parameter
  * check if autojump is installed
  * Merge pull request #784 from lnxbil/967e84ebaa180ad2ab1eebc9a512f94d93e84aea
  * Merge pull request #806 from OutPunk/terminalapp-plugin
  * Kill the compdef; Introduce 'grh' alias for 'git reset HEAD'
  * Added alias for git diff.
  * Merge pull request #816 from lucapette/add-annotate-to-bundler-commands
  * add annotate
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh into cloud_parameter
  * remove the -v flag from a few mercurial aliases
  * Git Plugin: adds 'grhh' alias for 'git reset HEAD --hard'
  * Apple Terminal.app resume directory plugin
  * autojump plugin enhanced
  * Merge pull request #785 from simonjefford/patch-1
  * Merge pull request #799 from plindborg/ruby-plugin-fix
  * Fixed the rfind command in the  ruby plugin
  * Merge pull request #790 from cicloid/master
  * add ability to set custom prefix for cloud theme
  * Get the Hostname
  * bundler plugin - don't "bundle exec rails"
  * correctly handle path names with spaces
  * multiple versions could occur and should also be highlighted
  * Mortal Scumbag Theme
  * make pygmalion theme use two lines when needed
  * Added vsplit_tab and split_tab for iTerm. Create new session within a vertical/horizontal split of the tab respectively.
  * Merge pull request #679 from ornicar/official
  * Merge pull request #671 from peterhoeg/31cddcd32427a5f5d3daa0da168d39aba5b510b4
  * Merge pull request #688 from alexstrat/master
  * Merge pull request #693 from dreur/upstream-debian-apt-history
  * Merge pull request #702 from sirech/fix-bundle-compl
  * Merge pull request #710 from moutten/patch-1
  * Merge pull request #669 from peterhoeg/f/battery
  * Merge pull request #618 from fceccon/custom-theme
  * Updating installation documentation to show a curl example as well for those who don't have wget installed.
  * Merge pull request #776 from mytechnix/master
  * Merge pull request #747 from ilikenwf/1a49f6443c0230b8e182294546ed9ef2a5110bf2
  * Merge pull request #764 from Fl4t/submodules
  * Merge pull request #772 from indrajitr/master
  * Merge pull request #765 from trevor/master
  * Merge pull request #768 from askreet/master
  * Merge pull request #769 from divineforest/master
  * Merge pull request #775 from tatey/sammy_black_on_white_theme
  * Added example aliases in ZSH template. Added a new theme.
  * Black on white theme inspired by Sam Stephenson's terminal screenshot on https://github.com/sstephenson/rbenv
  * Fix upgrade and uninstall functions to pick up $ZSH value
  * Added alias gcm='git checkout master
  * Added support for entries in /etc/ssh/ssh_known_hosts.
  * Ignore submodules dirty in prompt info
  * add note about custom plugins
  * Merge pull request #752 from andrewtch/symfony2-completion
  * Merge pull request #757 from cwjohnston/knife-environments
  * Merge pull request #759 from Zhann/master
  * show gemset next to ruby version
  * adding support for chef environments in knife plugin
  * Symfony 2 completion
  * Merge pull request #708 from eatnumber1/update-print
  * `setopt append_history` is not necessary.
  * Only `setopt correct`, not "correct_all".
  * add sprunge.us pastebin uploader - uses files, or pipes
  * Merge remote branch 'upstream/master'
  * Fixes and improves the behavior of the tm command
  * Merge pull request #343 from giddie/plugin-wakeonlan
  * Merge pull request #743 from c089/autojump-macports
  * Merge pull request #741 from suvash/master
  * Merge pull request #738 from pygatea/master
  * Merge pull request #733 from Zhann/master
  * Merge pull request #732 from ggustafsson/patch-1
  * Merge pull request #734 from maxpersson/726-pip-completion
  * Merge pull request #709 from docwhat/custom-plugin-fpath
  * Merge pull request #707 from gmcmillan/master
  * Merge pull request #706 from docwhat/termsupport-hook
  * Merge pull request #701 from kirs/master
  * Merge pull request #553 from benlumley/master
  * add support for autojump installed via macports
  * Added my own theme file : suvash
  * forks miloshadzic theme to add more directory info as well as user and host info
  * Merge remote branch 'upstream/master'
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * Added message when caching packages
  * Added caching of packages
  * Added brute force package completin on install subcommand
  * Adding critical security patch to let you all know I'm on top of this shit. add 'nyan' to your plugins... then run  for security upgrade.
  * Added Zhann theme. Based on Robbyrussel theme, but shows the current ruby version and has some color variations.
  * Removed duplicate setting and sorted the remaining
  * Jake-node plugin : update - remove the need to write a `jake_tasks` in the directory - use most recent usage of completion with zsh - tested for MacOSX and Ubuntu
  * tmuxinator completion
  * allow django-manage completion. http://pypi.python.org/pypi/DjangoDevKit
  * Only alias git=hub if `hub --version` works.
  * Update theme
  * Add the --format tag to knife list commands
  * Moved ZSH_CUSTOM declaration before fpath is set
  * set fpath correctly for custom plugins
  * Use printf rather than echo -e in update.sh
  * Added option to disable the update prompt. Set DISABLE_UPDATE_PROMPT to true to enable.
  * Added add-zsh-hook support to themes
  * lib/termsupport now uses add-zsh-hook
  * FIX: commands like ruby and rake where not being completed
  * Rails Migrations support
  * Add apt-history to debian plugin
  * Update completion for SSH
  * Adding custom theme
  * minor modifications in comment header (the revenge)
  * Minor modifications in comment-header
  * Added completion plugin for jake
  * update fino theme to work with rbenv
  * Add yaourt --sucre alias in archlinux plugin
  * Add zsh_reload which provides src function, this function will source .zshrc and rebuilds cache
  * fix: rbenv: I need to find a proper way to test changes...
  * add: rbenv plugin
  * add: battery plugin
  * add rails runner alias
  * Replace "git-diff" with "git diff" in the git plugin
  * RVM info
  * FrontCube theme with git status
  * Update the script to account for the changes in 0.1.7 where .gas is a directory
  * Do not overwrite EDITOR environment variable if already defined.
  * Comment
  * Merge remote-tracking branch 'upstream/master' into emacs
  * Fix builtin `ecd' when file path contains space characters.
  * Merge pull request #505 from masnick/master
  * Merge pull request #529 from dbb/master
  * Merge pull request #552 from Tricon/master
  * Merge pull request #579 from hakanensari/bundler-plugin-patch
  * Merge pull request #594 from sirech/fix-bundle-compl
  * Merge pull request #595 from zachriggle/grails-plugin
  * Merge pull request #554 from toolbear/549-fix-auto-upgrade
  * Merge pull request #607 from vddgil/patch-1
  * Merge pull request #613 from rkj/master
  * Merge pull request #614 from philippbosch/feature/terminitor-plugin
  * Merge pull request #622 from foozmeat/master
  * Merge pull request #626 from nickstenning/upstream
  * Merge pull request #631 from danshearmur/git-merge-alias
  * Merge pull request #645 from mr-szymanski/master
  * Merge pull request #648 from SFEley/d926a55872b5a12ab8b987e9d86c02358d0c825e
  * Merge pull request #418 from ptrv/master
  * Merge pull request #441 from Gonzih/master
  * Merge pull request #273 from blueyed/hub-alias-only-with-ruby
  * Merge pull request #225 from Soliah/plugin-bundler
  * Merge pull request #205 from sorin-ionescu/plugin-gnu-utils
  * Merge pull request #482 from volpino/master
  * Merge pull request #428 from matthewmccullough/gradleplugin
  * Merge pull request #338 from norm2782/master
  * Merge pull request #319 from sorin-ionescu/plugin-npm
  * Merge pull request #275 from tristan0x/require_tool
  * Merge pull request #274 from diofeher/master
  * Merge pull request #525 from kibs/master
  * Change default zshrc to export $ZSH (as required by check_for_upgrade.sh).
  * Fix up some wonkiness
  * Add new theme: wuffers
  * Show if you're ahead of remote in the wedisagree theme
  * added git merge as gm
  * Better cake completion: don't barf on options, and don't clobber user's namespace
  * This is the correct way to check the return value
  * This needs to explicitly check the return value
  * First search in the custom folder for the theme
  * Adding README file for the wakeonlan plugin
  * split rkj into two themes.
  * Splitting wakeonlan plugin completion into separate file
  * Forgot to quote the path parameter to wakeonlan
  * Tweaks to the wakeonlan plugin
  * terminitor plugin: add autocompletion also for edit, delete and setup subcommands.
  * terminitor plugin: add autocompletion for start subcommand.
  * Add basic autocompletion for terminitor (https://github.com/achiu/terminitor).
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * Textmate plugin update to take Gemfile and cucumber features in account
  * Added VCS prompt to Apple theme.
  * [plugins/grails] Remove warning message; it's always displayed
  * [plugins/grails] Use globbing instead of grep
  * [plugins/grails] Added grails plugin
  * fix completion for commands wrapped with bundler
  * New function `efile`
  * Merge branch 'master' of github.com:Gonzih/oh-my-zsh
  * vundle call fixed for new vundle version
  * add foreman, nanoc, and rainbows to list of bundled commands
  * order aliases alphabetically
  * Merge pull request #490 from hwti/428f18cf428fd86bd6e99c4363e5f25d0e392506
  * Merge pull request #408 from thunfischbrot/patch-1
  * Merge pull request #575 from mr-szymanski/master
  * Revert "Enable red dots during completion by default".
  * Add an alias for ga --> git add, too
  * Add gss alias for git status -s
  * Fix auto upgrade failure from non-exported ZSH env var
  * Rename to _capistrano (completion only)
  * Gallois theme - made the git branch/status show for those of us without rvm
  * Added nifty purple Apple theme.
  * Remove -s switch from apt-copy
  * oops, restore broken theme preview
  * detect rvm or rbenv and show ruby version
  * Merge pull request #545 from ches/patch-1
  * Add guard to bundler plugin's wrapped commands
  * Merge pull request #543 from dmondark/heroku-completion
  * Added a gradle build tool plugin
  * Heroku completion plugin
  * Merge pull request #492 from hwti/red-dots-completion
  * Merge pull request #512 from ichesnokov/master
  * Merge pull request #515 from rahult/feature/powder-plugin
  * Extend root ops, switch apt-copy to plain zsh
  * Add options for su(do) and apt(itude|-get)
  * Add functions for new GH repos.
  * Add functions for new GH repos.
  * Fix su commands
  * Merge "deb" and "debian" plugins.
  * Add bundle open alias, which open gem using EDITOR var
  * added option of setting another path to custom plugins and files
  * fixed theme chooser + options + list available themes + show all themes
  * add theme with command-line tips support
  * Added auto complete plugin for powder gem https://github.com/Rodreegez/powder
  * Fix edit-command-line binding
  * Merge in recent stuff
  * 'echo' did not show colors without -e in upgrade.sh
  * Merge pull request #464 from bkonkle/patch-1
  * Merge pull request #507 from walle/add_autocomplete_for_gas
  * Replace forgotten rubies with authors
  * Add autocomplete for gas. Based on the rvm plugin.
  * Add fino.zsh-theme
  * Enable red dots during completion by default
  * Merge pull request #494 from EspadaV8/master
  * Merge pull request #496 from semmons99/master
  * Merge pull request #502 from sunaku/history
  * move history-substring-search* files into plugins/
  * add alias for `bundle package` to the bundler plugin
  * The original SVN pluging would mark a folder as dirty if there was an svn:external set and the output of 'svn status' returned the check for the external. E.g.
  * Replace a duplicated test to see if we're in an SVN folder with a call to the 'in_svn' function.
  * Display red dots during completion process (disabled by default)
  * global zsh config
  * mac os fix
  * Add key bindings for gnome-terminal on Fedora
  * Merge pull request #488 from dreur/upstream-archlinux-plugin
  * Merge pull request #259 from dereine/master
  * Merge pull request #251 from kalasjocke/master
  * Merge pull request #215 from sunaku/history
  * Merge pull request #208 from sorin-ionescu/plugin-extract
  * Merge pull request #206 from sorin-ionescu/plugin-osx
  * Merge pull request #167 from jarinudom/master
  * Merge pull request #112 from lukerandall/master
  * fixing issue with last commit merge. missed a conflict
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * adding git svn aliases
  * added git log with graph
  * added mac keybinding for backward-delete-char
  * Merge pull request #412 from transat/master
  * Merge pull request #461 from dpoggi/master
  * Merge pull request #487 from dreur/upstream-spectrum-utility
  * More generic.
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Don't export oh-my-zsh configuration paramaters to the environment
  * Merge pull request #107 from philips/philips-theme
  * Merge pull request #484 from msabramo/f9bf396e4ac68299f1370ed54350cc14ce954eea
  * Remove sudo when using yaourt + do not rely on abs when not in path - In archlinux plugin
  * Add utility method to spectrum
  * Merge pull request #483 from dreur/upstream-archlinux-plugin
  * Fix typo
  * fox's theme + theme chooser fixes
  * added theme chooser
  * Merge pull request #480 from PabloSerbo/master
  * Bringing inline with oh-my-zsh coding convensions
  * Merge pull request #479 from csexton/edit-command-line
  * C-x C-e to edit current command in EDITOR
  * Merge pull request #474 from PabloSerbo/master
  * Merge pull request #476 from theunraveler/master
  * Merge pull request #452 from franklouwers/master
  * Merge pull request #468 from blinks/master
  * Merge pull request #477 from totolici/patch-1
  * Merge pull request #404 from gwjo/ssh-agent
  * Merge pull request #415 from eproxus/master
  * Merge pull request #475 from dreur/upstream-archlinux-plugin
  * Fixed typo for one of the subcommands (linset -> linsert)
  * Adding quotes to deal with paths that have spaces.
  * Added archlinux plugin
  * Completion for cake the coffee-script build tool
  * rsync: add rsync- prefixes and use aliases
  * Merge pull request #370 from lepht/taskwarrior-plugin
  * Merge pull request #451 from matthewmccullough/cloudappplugin
  * Merge pull request #467 from papercavalier/bundler
  * zsh-history-substring-search plugin at 15f63de
  * Added a new theme.
  * refactor _run-with-bundler
  * Minor corrections to deletion detection in git_prompt_status
  * Merge pull request #462 from papercavalier/bundler
  * clean up rails plugin, removing bundler-specific logic
  * alias bundle list
  * merge bundler and bundle-exec plugins
  * fix indentation
  * update bundled commands
  * Moved opening braces
  * forgot to rename one variable
  * changed names of functions and variables to fit naming conventions
  * use lowercase for variablenames
  * Added bundler-exec plugin
  * Added 'dpoggi' theme
  * knife autocompletion
  * added tip about vundle configutarion after git clone
  * vundle plugin refactored first it checks existens of vundle plugin, if plugin dont exist run git clone
  * Added cloudapp from @holman of @GitHub fame
  * Merge remote-tracking branch 'robbyrussell/master'
  * Updated the frisk theme to display Bazaar branch information as well (based on zedtux.zsh-theme http://j.mp/ikTZJj)
  * removing useless line
  * plugin for vundle (vim plugins managment system) that provide vundle, vundle-update and vundle-init aliases
  * Create gnzh theme
  * Merge pull request #429 from mhitza/master
  * Merge pull request #436 from smt/pull-request-1
  * Changed kanji to fuku (good luck)
  * Add ohmyzsh theme, my version of dogenpunk
  * rsync: add plugin
  * When the theme choice is left out, oh-my-zsh will not try to load it
  * use /home/ryan/d/.oh-my-zsh instead of ~/.oh-my-zsh for cache
  * Added mercurial plugin with aliases.
  * Add Django plugin. This is a slight modification of the Django zsh completions that I found at https://raw.github.com/technolize/zsh-completion-funcs/master/_manage.py
  * Fix MM lines being read correctly
  * Change plugin name from cap to capistrano
  * Rename guru theme to sunrise
  * Fix git R and M status when used together
  * Add note about Solarized color theme
  * Add email address
  * Merge remote-tracking branch 'robbyrussell/master'
  * Remove unused colors and use original prompt color
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Dollar sign instead of percent in unprivileged user prompt (as in real gentoo)
  * Included some essential aliases, inspired by http://lolcode.com/
  * New theme, Read contents for further customising.
  * Aliases
  * Merge pull request #400 from mkomitee/master
  * Add support for loading mulitple identities
  * Add support for agent forwarding
  * Fix bug from Pull request #395     #395 broke oh-my-zsh for users who disable check-for-updates
  * Merge pull request #395 from vguerci/upgrade-before-init
  * [upgrade] before init (no reload needed unless oh-my-zsh.sh has been modified)
  * Colorize Install & Upgrade Scripts
  * Merge pull request #371 from nebirhos/master
  * Merge pull request #378 from secondplanet/master
  * Merge pull request #391 from mattdoran/master
  * Fix typos in the svn plugin that would cause calls to 'svn' when not in an svn working copy.
  * Merge pull request #385 from sunaku/theme
  * add "sunaku" theme, see http://ompldr.org/vOHcwZg
  * Added gnu-utils plugin.
  * Handle tar.xz and tar.lzma better (credit: @gwjo).
  * Added extract plugin.
  * Added man-preview completion suggested by @webflo.
  * Vastly improved osx plugin.
  * Replaced npm 0.x completion with 1.0 completion.
  * Merge pull request #382 from miloshadzic/master
  * Merge pull request #380 from brianjriddle/master
  * Merge pull request #383 from alanpeabody/master
  * Adds my theme
  * Remove extra space when no status
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Revert "Added my zsh theme file, heavily based on sjl's" as it relies on a dotfile to be in ~/bin.
  * Merge pull request #375 from betawaffle/rollback-366
  * Merge pull request #381 from thePapacy/fix-git-zsh
  * Fix deleted in git.zsh
  * fix double -f and corrected format.
  * Improve unicode characters and git status
  * Add guru theme
  * added humza.zsh-theme
  * Remove Uneeded Lines
  * Rollback of Pull #366
  * Added nebirhos theme
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh into taskwarrior-plugin
  * Merge pull request #359 from theunraveler/master
  * Merge pull request #363 from Blattlaus/master
  * Merge pull request #366 from betawaffle/master
  * Merge pull request #368 from trapd00r/master
  * Merge pull request #365 from briankftse/master
  * add trapd00r theme
  * Fixed cap plugin
  * Merge branch 'plugins'
  * Thor
  * Cleanup
  * Add new 'minimal' theme
  * OS X Helpers
  * Node.js Helpers
  * Pow! Restart Helper
  * Brew Plugin
  * Gem List Helper
  * RVM Update Helpers
  * Helpful Listing Aliases
  * Ruby Switching Helpers
  * Added compatibility for the linux 'stat' command for the ant plugin
  * Added my own theme.
  * Adding ability to override plugins from the custom directory.
  * Merge pull request #345 from jacobat/master
  * Merge pull request #346 from jojahner/master
  * Merge pull request #196 from asymmetric/master
  * Merge pull request #226 from sunaku/fishy
  * Merge pull request #139 from clauswitt/master
  * Merge pull request #118 from fwalch/gpg-agent
  * Merge pull request #92 from re5et/master
  * Merge pull request #90 from steeef/steeef-theme
  * fishy theme: text indicators for $? and git status
  * Merge pull request #351 from GutenLinux/master
  * Merge pull request #347 from obcode/master
  * Merge pull request #355 from watsoncj/master^1
  * Adds oh-my-zsh plugin to load TaskWarrior completions
  * Adds the _task script included with TaskWarrior
  * Adds compl .swp caches to gitignore
  * Fix to random theme selection
  * Merge pull request #224 from Soliah/plugin-rvm
  * add custom completion support
  * Added obraun theme which is a slightly modified version of an already existing theme.
  * Added 'simple' theme.
  * Update, no more full path
  * TextMate automatically forks into the background
  * Add autojump plugin
  * Plugin to make WOL nice & easy
  * Add norm theme
  * Merge pull request #295 from alexrinass/apache2-macports-plugin
  * Merge pull request #290 from arthurkalm/delete-key-working
  * Merge pull request #322 from jonashuckestein/master
  * Merge pull request #324 from sorin-ionescu/plugin-compleat
  * Merge pull request #329 from juanghurtado/master
  * Merge pull request #330 from jtriley/jtriley-theme
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * remove git status from prompt
  * Adds support for $(current_branch) on git_parse_ahead()
  * Added Compleat - Completion for Human Beings plugin.
  * added my theme
  * Merge pull request #321 from nel/fix-window-title-regex.
  * Relax pattern matching on TERM. Closes #320.
  * Merge pull request #314 from mattsacks/master.
  * Merged pull request #315 from nebirhos/master.
  * Add fine-grained git prompt status to lukerandall.zsh-theme
  * fixed autoupdate
  * Add muse theme for 256 color terminals
  * Merged pull request #312 from juanghurtado/master.
  * Custom theme with Git support
  * Merged pull request #310 from Ikke/master.
  * Merged pull request #270 from sankara/d03a6176aacd583993c02c7e837d10751c431875.
  * Merged pull request #311 from papercavalier/rails3.
  * Rails 3 aliases now work with Rails 2 as well.
  * Added git-flow plugin
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Feature: Random themes now supported. Just set your theme to 'random' and it'll load a different theme each time oh-my-zsh is started. Closes #309
  * Merged pull request #308 from juanghurtado/master.
  * Adds new prompt methods on Git lib
  * Merged pull request #307 from jtriley/jtriley-theme.
  * Merged pull request #302 from JonathanTron/5bcfab37312511a7ffc3e8242ba8b8a622ecf061.
  * Merged pull request #303 from cit/master.
  * Merged pull request #299 from atmos/master.
  * Merged pull request #269 from oknowton/master.
  * Move sourcing of custom to below plugins
  * add my custom zsh prompt
  * add git-prompt plugin from olivierverdier/zsh-git-prompt
  * redis-cli.plugin.zsh removed, adding to the fpath isn't needed now
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * added alias for apt-cache search
  * Merged pull request #138 from murilasso/master.
  * Merged pull request #276 from saimn/yum.
  * Merged pull request #278 from totolici/redis-plugin.
  * Merged pull request #288 from dogenpunk/dogenpunk_theme.
  * Merged pull request #287 from arthurkalm/install-tweeks.
  * Merged pull request #294 from alexrinass/mysql-macports-plugin.
  * Merged pull request #297 from Soliah/master.
  * Merged pull request #298 from wolverian/master.
  * Merged pull request #300 from gallois/master.
  * added custom theme, based on eastwood
  * support non-standard rvm install prefixes
  * Add 'upgrade' to brew completions.
  * Made my them display the current rvm gemset and check for detached head state in git.
  * Added start/stop aliases for Apache 2 installation via macports.
  * Fixed folder naming for mysql-macports plugin and improved start/stop scripts.
  * Remove fpath/compinit code from github and npm plugins
  * Merge remote branch 'upstream/master'
  * Added bindings for Gnome terminal.
  * Make the delete key work correctly, instead of outputting a ~
  * Changed to use which.
  * Change URL to https since most corporate environments block git port.
  * Make the chsh more reliable.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Add new jonathan theme
  * Fix indentation
  * Fix alias `eeval'
  * - Fix pass of parameters - Add new function `ecd'.
  * redis-cli completion plugin
  * refactored pycrm command
  * More comments
  * I should not have merged this here.
  * new yum plugin with useful aliases
  * Removing master stuff
  * Merge branch 'master'; commit 'ca4dabb45e14d8cd38e07c4ffadf9473ceb2193b' into require_tool
  * Add new plugin emacs, to take benefit of daemon capabilities of emacs >=23
  * Fix version parsing. Now working with command $ zsh --version
  * New tool require_tool.sh
  * adding python plugin with some aliases
  * New plugin git-svn installing git project git-svn-clone-externals
  * Minor reformatting
  * github plugin: check for `ruby`.
  * Moved the plugin fpath loop and compinit so they happen before custom scripts are loaded.
  * Optimize plugin loading so that only one call to compinit is required
  * Moved compinit call back to oh-my-zsh.sh, after plugins are loaded
  * Add: new theme
  * Merge branch 'friskTheme' of https://github.com/Nycto/oh-my-zsh
  * Added the Frisk theme
  * Updating the README... now links to contributors page
  * kolo.zsh-theme
  * changes recommended by blueyed
  * Whoops, this was supposed to be in the last commit!
  * Moved this to the existing github plugin
  * blueyed's ZSH-fu is much stronger than mine.
  * no need for an extra fork
  * added hub plugin from defunkt
  * Revert "Enable alias completion, do not limit completion to just files"
  * Added npm plugin.
  * Using git-diff instead of git diff
  * Removing call to mate.
  * Fix `gdv`: make it a function, and use `view`.
  * Removed commented out code.
  * Moved the single compinit call from oh-my-zsh.sh to lib/completion.zsh
  * Replace redundant calls to compinit with a single call.
  * Refactor DISABLE_AUTO_TITLE to be more DRY
  * Command title behavior no longer depend on local zsh configuration
  * Escape characters used in escape sequence to avoid triggering bugs in Apple Terminal
  * Further git completion improovements
  * Completions are git subdommand-aware now
  * Zsh will now complete git aliases with git stuff
  * Merge branch 'disable_auto-title' of https://github.com/lorrin/oh-my-zsh into lorrin-disable_auto-title
  * Adding dogenpunk theme
  * Add a plugin to support kate the kde texteditor
  * fixed wget command in readme
  * Introduce DISABLE_AUTO_TITLE option
  * Make command-not-found no-op when support not available (e.g. not on Ubuntu)
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Lein completion
  * New theme 'intheloop' which demonstrates the git_remote_status function
  * Added new function git_remote_status to check if we are ahead, behind or diverged from the remote branch
  * Added terminal party theme.
  * Added the Frisk theme
  * Revert "Re-order title/tab setting to make window titles work on OSX terminal which" Was causing iTerm title to disappear entirely..
  * Merge branch 'ssh-agent-append-host-to-environment' of https://github.com/trcjr/oh-my-zsh into trcjr-ssh-agent-append-host-to-environment
  * Merge branch 'master' of https://github.com/AlexBio/oh-my-zsh into AlexBio-master
  * Merge branch 'osx-terminal-title' of https://github.com/curiousstranger/oh-my-zsh into curiousstranger-osx-terminal-title
  * Merge branch 'master' of https://github.com/dbbolton/oh-my-zsh into dbbolton-master
  * Merge branch 'feature/alias-completion' of https://github.com/shadowhand/oh-my-zsh into shadowhand-feature/alias-completion
  * Merge branch 'master' of https://github.com/tjkirch/oh-my-zsh into tjkirch-master
  * Add debian plugins file
  * No space before prompt char at beginning of line
  * Actually show return code on failure
  * Sweet lightning bolt on uncommitted git changes
  * Remove unnecessary whitespace
  * Make personal theme based on dst
  * add Perl plugins file
  * Re-order title/tab setting to make window titles work on OSX terminal which doesn't support tabs titles.
  * Add completion for port command
  * add 'deb' plugin with Debian's apt aliases
  * add completion plugin 'cpanm' for cpanminus
  * add 'lol' plugin (based on lolbash)
  * Enable alias completion, do not limit completion to just files
  * Merge ssh://spix-dev01/home/fredrik/.oh-my-zsh
  * figuring out home dir on unix systems as well
  * Merge branch 'master' of github.com:fred-o/oh-my-zsh
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * fix to avoid parse errors if $TERM is empty
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * Added a plugin for GNU Screen.
  * .gitignore
  * ssh-agent plugin now ends in "-$HOST" so an agent is started properly with nfs shared homes.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Refined RVM prompt in Crunch theme
  * Crunch theme (by Stephen Eley)
  * Add tab completion to bundler plugin.
  * Add tab completion for rvm.
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * no hg & git status (sloooow)
  * Merge branch 'master' of https://github.com/myronmarston/oh-my-zsh into myronmarston-master
  * Merge branch 'refactor-term' of https://github.com/nel/oh-my-zsh into nel-refactor-term
  * Merge branch 'master' of https://github.com/medwezys/oh-my-zsh into medwezys-master
  * Merge branch 'osx' of https://github.com/benlangfeld/oh-my-zsh into benlangfeld-osx
  * Merge branch 'master' of https://github.com/Soliah/oh-my-zsh into Soliah-master
  * Merge branch 'lib-git' of https://github.com/sorin-ionescu/oh-my-zsh into sorin-ionescu-lib-git
  * Merge branch 'master' of https://github.com/nanotech/oh-my-zsh into nanotech-master
  * Merge branch 'theme-sorin' of https://github.com/sorin-ionescu/oh-my-zsh into sorin-ionescu-theme-sorin
  * Merge branch 'master' of https://github.com/Nemo157/oh-my-zsh into Nemo157-master
  * Merge branch 'nicoulaj-theme' of https://github.com/nicoulaj/oh-my-zsh into nicoulaj-nicoulaj-theme
  * Add iTerm version of tab function (itab)
  * Make a cleaner version of the OS X tab function
  * Renamed theme.
  * Added my theme.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * mvn plugin
  * Add bundler plugin with aliases.
  * Should use https for all GitHub urls.
  * fixed typo in rails3 plugin and added one alias for migrating and redoing migration if it was successful
  * Merge branch 'master' of github.com:fred-o/oh-my-zsh
  * Add vagrant completion for individual VMs
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * Added modified while newly added and type change detection to git prompt modified status.
  * Fixed auto update.
  * Added sorin oh-my-zsh theme.
  * Added time since last commit to Soliah theme and changed some colours.
  * Refactor window and tab title in tty
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * add missing unrar flag
  * Merge branch 'master' of https://github.com/theunraveler/oh-my-zsh into theunraveler-master
  * Merge branch 'master' of https://github.com/SuprDewd/oh-my-zsh into SuprDewd-master
  * Merge branch 'postpone-theme-sourcing' of https://github.com/mkomitee/oh-my-zsh into mkomitee-postpone-theme-sourcing
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of https://github.com/Rixius/oh-my-zsh into Rixius-master
  * Merge branch 'dieter-theme' of https://github.com/Dieterbe/oh-my-zsh into Dieterbe-dieter-theme
  * Merge branch 'typo' of https://github.com/papercavalier/oh-my-zsh into papercavalier-typo
  * Merge branch 'master' of https://github.com/sunaku/oh-my-zsh
  * Merge branch 'master' of https://github.com/dannytatom/oh-my-zsh into dannytatom-master
  * Merge branch 'master' of https://github.com/flazz/oh-my-zsh into flazz-master
  * added newline
  * Personal Style
  * theme changes
  * changes to theme
  * add Rixius-Theme
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Added an option to remove file afterwards.
  * Added svn info in prompt with plugin.
  * Made git ignore everything  in custom, not only the .zsh files.
  * theme based on afowler with vi-mode support
  * Added lambda theme
  * Postponing sourcing of the theme until after local customizations
  * avoid forking subshell to test if user is root
  * Merge branch 'git' of https://github.com/papercavalier/oh-my-zsh into papercavalier-git
  * Merge branch 'master' of https://github.com/derekprior/oh-my-zsh into derekprior-master
  * Merge branch 'rails3' of https://github.com/papercavalier/oh-my-zsh into papercavalier-rails3
  * add "fishy" theme to emulate Fish shell's prompt
  * Support for more archive formats.
  * Added a function to extract various archives. Also an alias for the function.
  * Added function to mkdir and immediately change to it
  * Add superjarin theme that shows current Ruby version via RVM
  * Typo
  * Removed remote_console. It doesn't handle rvm, capistrano, and so on.
  * A rails3 plugin based on the rails plugin
  * Aliased git checkout as `gco`
  * Fixed typo
  * Updating theunraveler theme to include more detailed git info.
  * Merge branch 'kardan' of https://github.com/kardan/oh-my-zsh into kardan-kardan
  * Updated the PROMT.
  * Added new kardan theme.
  * gentoo-like theme w/ git_prompt_info
  * Don't export oh-my-zsh configuration paramaters to the environment
  * maven plugin
  * Merge branch 'master' of github.com:clauswitt/oh-my-zsh
  * Added ant plugin
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * better phrasing/documentation
  * reset exit code visual cues (not exit code itself) after showing once
  * add dieter theme v1
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Avoid duplicate path cropping
  * Add my prompt theme
  * Rename appearance.zsh so that it gets loaded after spectrum.zsh. Allows to use 256 colors in prompt themes.
  * changes
  * Merge branch 'fix-lighthouse-error-message' of https://github.com/mortice/oh-my-zsh into mortice-fix-lighthouse-error-message
  * Merge branch 'completions' of https://github.com/gwjo/oh-my-zsh into gwjo-completions
  * Merge branch 'joerc' of https://github.com/sargas/oh-my-zsh into sargas-joerc
  * Merge branch 'master' of https://github.com/Bira/oh-my-zsh into Bira-master
  * Merge branch 'master' of https://github.com/FedyashevNikita/oh-my-zsh into FedyashevNikita-master
  * Removed the echo statement - no need for that.
  * improved formatting; redundant attributes deleted
  * fixed formatting; dead code deleted
  * vagrant plugin autocompletion - initial version
  * themes/nanotech: Use the new built-in zsh color variables.
  * Added my own theme, based on macovsky-ruby and funky
  * Added phing plugin
  * Merge remote branch 'origin/master' into gpg-agent
  * Completion fixes
  * Fix lighthouse plugin error message
  * command-not-found package in ubuntu
  * merge from master
  * merge theme fixes from master
  * merge with master
  * merge with master
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Added gpg-agent plugin
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * Added own theme (based on robbyrussell)
  * themes: philips customize git/ls for developers
  * merging in changes from robby's repo
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * bugfix - moved gem info
  * Merge branch 'master' of http://github.com/svnlto/oh-my-zsh into svnlto-master
  * Merge branch 'master' of http://github.com/philtr/oh-my-zsh into philtr-master
  * Merge branch 'philips-theme' of http://github.com/philips/oh-my-zsh into philips-philips-theme
  * Merge branch 'title-fix' of http://github.com/philips/oh-my-zsh into philips-title-fix
  * changeing unicode characters that were causing issues
  * leaving out subcommands for now
  * adding comment and URL to github gem
  * added git log incl. stats for the past 5 commits
  * adding github plugin
  * themes: add philips theme
  * functions: fix title() to not match any $TERM
  * Fixing some minor redrew issue
  * Adding new gozilla theme
  * Improving git plugin so it can display much more data.
  * Add cloud.zsh-theme
  * merge master
  * use 256 colors, if available
  * should have newline at end of file.
  * adding my zsh-theme
  * added rkj theme - xion-chiamiov-plus + hg from thomasjbradley
  * fix untracked files checking
  * merge steeef.zsh-theme from master (removed submodule check)
  * merge steeef.zsh-theme from master
  * Removing capistrano aliases/functions from rails plugin (since cap is not rails-specific).
  * Add lukerandall.zsh-theme
  * adapt brew,gem,pip plugin to new structure
  * Merge remote branch 'origin/master' into restructure_plugins
  * Reorganizing plugins so that each plugin has it's own directory now so that any plugin-specific functions can be bundled within there.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of http://github.com/kennethreitz/oh-my-zsh into kennethreitz-master
  * Merge branch 'master' of http://github.com/vivekprahlad/oh-my-zsh into vivekprahlad-master
  * Merge branch 'dirpersist' of http://github.com/curiousstranger/oh-my-zsh into curiousstranger-dirpersist
  * Match xterm-color, the default OS X terminal
  * Tidying up the spacing to bring in line with coding standards
  * Merge branch 'ssh-agent' of http://github.com/gwjo/oh-my-zsh into gwjo-ssh-agent
  * Merge branch 'theunraveler_theme' of http://github.com/theunraveler/oh-my-zsh into theunraveler-theunraveler_theme
  * Merge branch 'named_dirs_completion' of http://github.com/kremso/oh-my-zsh into kremso-named_dirs_completion
  * Merge branch 'shifttab' of http://github.com/kremso/oh-my-zsh into kremso-shifttab
  * added steeef theme
  * Portable perl dirpersiststore because 'tail -r' doesn't work everywhere.
  * Add vi-mode plugin for vi-like editing
  * Do not complete named-directories
  * unset config_file is useless
  * Added theunraveler theme.
  * ssh-agent module
  * Removed unportable (and unnecessary) grep flags
  * Change zdirstore to variable
  * Added install instructions
  * Added installation function
  * Move dirpersist to plugin
  * Escape some metachars that trip up .zdirstore script
  * Escape &'s in path name.  Need to find general function for escaping all shell metacharacters.
  * Alias popd to remove deleted dirs from persistance
  * Initial pass at pesistant directory stack
  * Adding comments
  * Adding a plugin with aliases for macports
  * Merge branch 'pip_plugin'
  * Merge branch 'gem_plugin'
  * Merge branch 'brew_plugin_fix'
  * add pip completion and plugin
  * add gem completion function and plugin
  * Added the truly epic kennethreitz theme.
  * Removing '.' alias as it is overwriting a bash/zsh feature. Closes #63
  * fix problems with brew completion
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Switching to /usr/bin/env zsh instead of /bin/zsh in the installer
  * add fletcherm theme; a slightly modified copy of an old tonotdo theme
  * add simple mrtazz theme based on robbyrussell
  * update brew plugin from homebrew contributions
  * Merge branch 'master' of http://github.com/AlexBio/oh-my-zsh into AlexBio/master
  * Made the user_machine_size calculation generic. Pwned the function name.
  * Added my own theme based on pat's
  * add candy theme
  * Added my theme (nanotech).
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Adding a ggpnp which does a git pull followed by a git push.
  * updated the readme
  * added plugin to control macports mysql-server installation
  * Added my own theme.
  * Don't correct hpodder commands.
  * Added a minimum zsh version note.
  * Don't display dotfiles or reverse sort with ll alias.
  * Ignore commands that start with a space.
  * Don't auto-correct ebuild commands.
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Adding some candy to the upgrade script
  * Moving brew functions to it's own plugin
  * Moving current_branch() to git plugin
  * Moving some rails and osx-specific functions to their corresponding plugin files
  * Removing legacy completion code
  * Removing rake completion from lib/ as it was moved to rails plugin
  * Moving capistrano functions to rails plugin
  * Updating default .zshrc template file to include plugins declaration
  * Initial implementation of a new plugin system, so that people can managed which aliases/functions they want.
  * Eastwood theme with optional RVM support
  * adding my zsh theme -- only difference from robby's being that i'm using white instead of blue for legibility over brown
  * Added customized version of the wezm theme (mainly added username/host in the prompt).
  * Added my zsh theme file, heavily based on sjl's
  * aussiegeek theme (include showing rvm prompt)
  * Import rvm prompt
  * macowsky modified theme with ruby version on prompt
  * modified macovsky to support ruby version
  * Adds a new theme that only seems to work on Linux
  * Sprinkling some candy on this muffin.
  * added skaro theme
  * added my theme
  * New theme "daveverwer", based on "geoffgarside".
  * added my own theme
  * happy with my theme. caret turns red for root
  * my WIP theme
  * Added my own theme.
  * Add my preferred prompt
  * added the dstufft theme (based on prose by sjl)
  * Add my oh-my-zsh theme
  * share history with your zsh's on the same host
  * added my theme, based on xiong-chiamiov-plus but using vcs_info instead of just git
  * two aliases set to 'ss', clobbering rails script/server
  * my theme
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Merge remote branch 'NV/master'
  * Adds new duellj theme
  * Merge remote branch 'jreese/master'
  * updated my theme with the date and git branch (+ dirty or not)
  * Merge remote branch 'robbyrussell/master'
  * Unsetting config_file after loading config
  * Don't autoselect first completion entry (Fixes #14)
  * Removing rake autocompletion as this is apparently  baked into recent versions of zsh
  * Fixed color in last character of clean git info
  * 256 color theme with bright blue and orange
  * escape sequences so rprompt doesn't mess up
  * Added scpectrum script for easy 256 color theaming
  * makes git status prompt 4x faster
  * Ignore errors from compaudit when using `sudo -s`
  * Remove limit of two segments to PWD
  * Added screenshot link for jreese theme
  * Added theme "jreese" to oh-my-zsh
  * Make Shift+Tab move backwards in the menu
  * added my personal theme: the dallas them
  * git:(master) --> git:master Parenthesis removed
  * Arrow theme: http://elv1s.ru/i/zsh-arrow-theme.png
  * clean theme: username is now bold
  * improvements to the 'clean' theme
  * added "clean" theme
  * fork xiong-chiamiov theme for git support
  * Putting Git related aliases into git.zsh to have them in context.
  * adding quotes to tab()
  * Adding a function that will open up a ticket in Lighthouse based on the number and there being a URL in a hidden file.
  * Adding a nocorrect for the heroku command as it was getting triggered by heroku logs.
  * Based on a suggestion from robbyrussel, using env for greater compatibility.
  * Instead of using the user's standard shell, this script should be run using zsh, since that was the shell it was written for.  On my machine changes to my default shell only take effect when I log out and then long in again.  Plus, it's nice for people to be able to try oh-my-zsh out even if zsh isn't their default shell right?  :-)
  * Merge commit 'e429ff9e2bed41f88e3df3315b159fa79a7152fc'
  * Merge branch 'master' of git://github.com/macovsky/oh-my-zsh into macovsky/master
  * Updating check_for_upgrade script to fix issue when the LAST_EPOCH file/value got corrupted. Closes #32
  * no correction on gist
  * new theme
  * No correction on mkdir + removed duplicate nocorrect mv
  * Revert
  * Completion from history
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Adding current_branch function, which can be used like: git pull origin master
  * tonotdo theme: Back to the original
  * tonotdo theme still not like I wanted
  * tonotdo theme like I like it
  * Theme tonotdo upgrade
  * Gallifrey theme
  * gave credit to Nick for the rake autocompletion code.
  * Spiced up the tonotdo theme, some more
  * Spiced up the tonotdo theme
  * LS_COLORS fix for tonotdo theme
  * Improved the LS_COLORS in my tonotdo theme
  * Fixed all themes so tab-completion doesn't move the cursor to a weird position
  * Modifying changes for issue 25, to fix issue 27
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Revert "Added my prompt theme, with a tweak to the core oh-my-zsh to support it. My git_prompt_info function not only reports the branch and dirty status, but also whether or not the branch is ahead or behind of the remote, or both. It also switches the prompt colour from green to red if the previous command exited with a non-zero value (i.e. failed)."
  * Revert "Whoops, forgot to include this dummy precmd implementation."
  * Only using the contents of .ssh/known_hosts when the file exists for ssh/scp auto-completion. Closes issue #20
  * Removing gdb alias as it conflicts with an actual command for gdb. Closes #17
  * Revert "Fixed issue #19 'Rake not auto completing'.  The stat command syntax that was being used was not correct. Or at least on my machine.  See man page for the stat command"
  * Added initial jnrowe theme.
  * Fixed issue #25.
  * Fixed darkblood theme as in issue #23.
  * Whoops, forgot to include this dummy precmd implementation.
  * Added my prompt theme, with a tweak to the core oh-my-zsh to support it. My git_prompt_info function not only reports the branch and dirty status, but also whether or not the branch is ahead or behind of the remote, or both. It also switches the prompt colour from green to red if the previous command exited with a non-zero value (i.e. failed).
  * parse error fix
  * Enabled colors in ls and made it possible to theme them
  * added LSCOLORS
  * Joined the appearance so the theme can apply LSCOLORS too
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Adding devlog alias for tailing development.log for Rails
  * Skip the git word in this theme
  * Small fix, probably the smallest possible
  * Added my theme
  * Added darkblod theme.
  * Fixing some conflict residue that I missed in a commit/merge:
  * Merge branch 'master' of git://github.com/kastner/oh-my-zsh into kastner/master
  * Merge branch 'master' of git://github.com/mrinterweb/oh-my-zsh into mrinterweb/master
  * Fixing merge conflicts 886d97f41e72b8662232a2c6b196fb60508e4f67
  * lsa now uses coloring
  * ll doesn't show hidden files, lsa does
  * Merging conflict. 788c9af05684f4b9e39e7f15de2c06c4c8291cbd
  * Merge branch 'master' of git://github.com/mdonoughe/oh-my-zsh into mdonoughe/master
  * adding homebrew completions - and a function dir
  * Fixed issue #19 'Rake not auto completing'.  The stat command syntax that was being used was not correct. Or at least on my machine.  See man page for the stat command
  * Removed useless else
  * Fixing merge
  * extended path variable, temporary
  * Renaming script/server --debug alias to ssd to avoid conflict. Closes #1
  * added gcp alias (git cherry-pick)
  * Added some comment
  * Merge branch 'master' of git://github.com/wezm/oh-my-zsh into wezm/master
  * Merge branch 'cypher/master'
  * Added more aliases for Rails & git
  * Added ack-grep searching
  * Added git diff for vim (gdv)
  * Replaced source with .
  * Add my own theme
  * should probably use the value of CASE_INSENSITIVE
  * allow case sensitivity to be toggled
  * Fix cypher's theme for older zsh versions
  * Merge branch 'master' of git://github.com/cypher/oh-my-zsh into cypher/master
  * add xiong-chiamiov theme
  * Make "-" an alias for "cd -" (cd back to previous directory)
  * Add my (cypher's) zsh prompt
  * run update check *after* running custom configuration scripts. This means we are running it after $PATH has potentially been set up, which means it's more likely that commands like "git" will be found
  * Oh My Zsh gets a weekly auto-updater... the future is now!
  * Adding a script to check for upgrades
  * put everything in lib
  * merge upstream
  * Bumping up history to 10k commands
  * Updating README to mention custom/ directory
  * not ignoring example.zsh
  * Updating .gitignore to ignore everything but the example.zsh file in custom/
  * Moving some example files into custom/
  * Moving all zsh config options into a lib/ subdirectory to make way for some upcoming changes to directory structure and configuration options
  * Using compctl instead of compdef to resolve Issue #1
  * Merge remote branch 'upstream/master'
  * add in refcard note
  * more fixes, more or less have this as i want
  * further refactorings
  * misc useful
  * tidy up history
  * Added a new theme
  * would rather store history in $HOME and double size
  * some todo notes, take @chris2's titlebar improvements and poke at completions
  * minimalist
  * add in xterms / title hacks
  * Merge remote branch 'upstream/master'
  * Git 1.6 support
  * Improved git prompt handling
  * make correction work; this is a nicer way of handling typos in commands
  * some helpers to make directory traversal go easier....
  * Adding a little documentation for the git themes
  * Added risto theme and made git.zsh themable
  * Updating the name of the rake and capistrano task cache file to append a ~ to the end of the filename so it's easier to ignore in rails git projects. [#1]
  * Updating install process to copy your current environments PATH and adding it to the bottom of ~/.zshrc.
  * Merge branch 'master' of git://github.com/mwilliams/oh-my-zsh into mwilliams/master
  * added case-insensitive auto completion
  * Adding more useful aliases for Git.
  * Moving bindings into their own file. Updating aliases after moving out bindings
  * Trying out some zsh-fu. Using the for x (*.zsh) source  approach
  * Updating README to instruct people to copy the .zshrc template file versus symlinking it.
  * Updating installer to use the new template file. ~/.zshrc will now be outside of the repository
  * Updating the template file to use the oh-my-zsh.sh loader
  * Renaming template file one last time (for now)
  * Moving and renaming the zshrc file to a template file
  * Moving the loading of all .zsh files into a different file so that we can remove zshrc from the repository
  * Including a link to the Themes wiki page from the README
  * Added extra theme with full pathnames and hostname
  * Adding an upgrade_oh_my_zsh function to... well, upgrade Oh My Zsh
  * Removing left over theme reference to geoffs theme
  * Merging geoffgarside work
  * Adding an uninstaller tool
  * Adding zsh_stats function to show you which commands you run the most.
  * Move the spaces around again :P
  * Merge branch 'master' of git@github.com:geoffgarside/oh-my-zsh
  * Only calling git symbolic-ref HEAD when we are in a .git directory
  * Restructure spaces in git pieces
  * Switch double quotes for singles, fixes prompt issues
  * Add my own theme
  * Colour branch name and add dirty string
  * Change dirty git string to a yello X
  * Remove colour from ls command
  * Adding a file into log/ so that we have a log file to record history to
  * Remove PATH definition as we define this in .profile
  * Add geoffgarside theme
  * Merge branch master
  * Adding Evan's skinny, topless prompt.
  * Updating README with info about themes
  * Adding theme support so that people can share their zsh prompts with others. Users can set which theme to load in zshrc now.
  * Add tab, take and tm functions
  * Customise prompt value
  * Use my normal PATH instead of included
  * Strip colours from git.zsh
  * Swap out g alias to git
  * Add textmate aliases
  * Add in my normal s{s,d} aliases
  * Updating README to match new path for installation.
  * Changing order of loading zsh at end of install
  * Attempting to load zsh properly after auto-install
  * Checking if .zshrc is a file or a symlink.
  * Updating README with reference to auto-installer
  * Adding an installer tool
  * Adding a note about backing up your existing zshrc file
  * Updating README to show people how to change their default shell.
  * Removing some unused git-dirty parsing code.
  * Removed a bunch of aliases that I never use, which came from someone else I copied old config from
  * Removing a robby-only alias
  * Moving some more config into prompt.zsh to reduce amount of code in .zshrc
  * Info about contributing
  * Updating README regarding PATH info
  * Note about PATH
  * Making sure it's obvious to symlink to ~/.zshrc
  * Merge branch 'master' of git://github.com/eddorre/oh-my-zsh into eddorre/master
  * Adding some info to the Usage section of the README
  * Updating README
  * Loading all files in /Users/robbyrussell/oh-my-zsh that end in .zsh instead of specifying them manually
  * Removed Git Aliases comment since there are no Git aliases in this file
  * Updating README file
  * Changing path to oh-my-zsh in zshrc
  * Importing initial files after reorganizing stuff.
  * Adding initial gitignore file

n.n.n / 2014-04-14 
==================

  * Merge pull request #2685 from delynn/patch-2
  * Remove mailcatcher
  * Merge pull request #2329 from pstadler/brew-cask
  * Merge pull request #2663 from bobmaerten/docker-autocomplete-updates
  * Merge pull request #2651 from jehrhardt/fix-emacs
  * Merge pull request #2661 from mcornella/fix_title_tab_percent
  * Merge pull request #2659 from simonc/allowing-pow-path-with-spaces
  * Merge pull request #2658 from leifcr/rake-fast-issue
  * Merge pull request #2647 from bobwilliams/master
  * Merge pull request #2656 from philenotfound/master
  * Merge pull request #2652 from lukehorvat/patch-1
  * Merge pull request #2660 from KevinBongart/add-readme-to-rake-fast
  * Merge pull request #2662 from aeriksson/master
  * adding urldecode_json to compliment urlencode_json and updating readme.md; slight tweak to urlencode_json from previous commit
  * adding urlencode_json and associated README.md details
  * Matching autocomplete for Docker v0.9.1
  * Fix broken reverse-menu-complete keybinding.
  * adding the is_json tool and associated readme.md details
  * Escape % in $CMD variable
  * Add README file to rake-fast plugin
  * Allowing path with spaces in pow plugin
  * brew-cask plugin: use spaces instead of tabs
  * Merge branch 'master' of github.com:philenotfound/oh-my-zsh
  * New aliases for 'apt-get' and 'aptitude' as they were overwritten by later aliases
  * adding support for node
  * Adds command line aliases useful for dealing with JSON
  * Updates spectrum.zsh
  * $ZSH is the OMZ installation folder, not configuration
  * mention $ZSH_CUSTOM as suggested in #2295
  * suggest setting $LANG to fix #1286 and fix #1823
  * Fix export syntax of $GREP_OPTIONS
  * Rendering the 'vagrant box (remove|repackage)' completion code independant of Vagrant implementation details.
  * application completion
  * library completion
  * in hindsight, this is probably a bad idea
  * completion of targets
  * instance and cluster completion
  * node completion
  * help command, node completion
  * added _files values for certain options
  * completion options
  * added alias
  * added completions for all known arguments to all known commands
  * apparently, this file must exist for the plugin to load
  * added completion for all asadmin subcommands
  * avoid VCS folders
  * Move example plugin to the custom plugins dir.
  * Add completion for pip install -r - so that it autocompletes requirements filenames
  * Added an <esc> to the begining of everything. I ran something when I was in insert mode once and all it did was shove !args... into the buffer.  <esc> first.
  * Updated the README to include documentation on the postCallVim callout
  * Added an optional callout to the end of the interaction function. I put it in to allow me to put the window focus on MacVim / GVim depending on the different OS I happen to be on
  * Fixed: If you callvim on a non-existant file with a relative path, the CWD of the running gvim process is used, and that's not right.  We use the PWD explicitly instead, in this case
  * A plugin that makes it easier to interact with the (single) running instance of gvim
  * command to restart pow process
  * added powed command to list pow urls
  * fix gnzh theme to detect local rvm installations
  * Added link to wiki page for plugins to README.
  * Add gem build autocompletion
  * `setopt append_history` is not necessary.
  * Plugin: Rake-fast: Support both *nix and Darwin
  * New aliases for 'apt-get' and 'aptitude' as they were overwritten by later aliases
  * Fixed typos + made wording more consistent in zshrc.zsh-template
  * adding xargs -0 to node aliases
  * updated readme.md and using tab char for formatting with node
  * bug fix for node pp_json version
  * Add check for display list equals nil
  * updating README.md
  * adding README.md for jsontools
  * Merge pull request #2563 from bobwilliams/master
  * Merge pull request #2390 from LFDM/updating_spectrum
  * Merge pull request #2645 from ncanceill/template-zshrc
  * Merge remote-tracking branch 'upstream/master'
  * $ZSH is the OMZ installation folder, not configuration
  * mention $ZSH_CUSTOM as suggested in #2295
  * suggest setting $LANG to fix #1286 and fix #1823
  * Merge pull request #2643 from mcornella/patch-1
  * Merge remote-tracking branch 'upstream/master'
  * Fix export syntax of $GREP_OPTIONS
  * Merge pull request #1302 from cybozuty/master
  * Merge pull request #1262 from fred-o/glassfish-plugin
  * Merge pull request #1162 from nXqd/patch-1
  * Merge pull request #1117 from Peeja/move-example-plugin
  * Merge pull request #967 from wjlroe/pip-requirements
  * Merge pull request #1022 from derekwyatt/master
  * Merge pull request #1005 from cmar/powed
  * Merge pull request #995 from wting/fix_gnzh_ruby_detection
  * Merge pull request #990 from tommorris/master
  * Merge pull request #973 from dlee/gem_build
  * Merge pull request #750 from blueyed/history-drop-default-append-history
  * Merge pull request #672 from eMxyzptlk/zsh_reload
  * Merge pull request #662 from walle/add_autocomplete_for_gas
  * Merge pull request #646 from whittle/master
  * Merge pull request #2618 from bdubertret/fix-gwip-norm
  * Merge pull request #2634 from danchenkov/master
  * Merge pull request #2638 from miguelfrde/irb
  * Merge pull request #2605 from mhauserr/patch-1
  * Merge pull request #2615 from erbridge/fix_virtualenvwrapper_lazy
  * Merge pull request #2616 from Bounga/master
  * Merge pull request #2620 from reedriley/master
  * Merge pull request #2619 from korylprince/master
  * Sort bundled commands alphabetically
  * Merge pull request #2440 from m0nah/master
  * Merge pull request #2510 from pavoljuhas/master
  * Merge pull request #2531 from KevinBongart/rake-fast
  * Merge pull request #2637 from aforty/master
  * Merge pull request #2627 from loxley/add_knife_vault_cmd
  * Merge pull request #2631 from AntoineD/master
  * Merge pull request #2639 from jieryn/master
  * add common video formats FLV and WEBM
  * Add irb to the list of bundled commands
  * Merge pull request #1 from KevinBongart/brew-cask
  * Add new brew cask commands
  * Added a forward-delete fallback to bind Delete key
  * atom plugin
  * Aligned comments
  * Update key-bindings.zsh
  * added terminfo keys verification
  * Fix dirpersist plugin
  * Fixed errors if acpitool isn't installed on linux
  * Add chef-vault knife cmd support
  * Add scd plugin for smart change of directory.
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Don't show useless '[]' when chruby_prompt_info is empty
  * Fix gwip alias in git plugin when no files to rm
  * Merge remote-tracking branch 'upstream/master'
  * Don't set RBENV_ROOT to "$HOME/.rbenv" when using Homebrew rbenv
  * Merge pull request #2576 from jeffwilliams/master
  * Merge pull request #2597 from githubhjs/master
  * Don't lazy load the virtualenvwrapper.
  * Merge pull request #2539 from chriswiggins/master
  * Merge pull request #2549 from brandon-beacher/master
  * Merge pull request #2574 from thiagowfx/linux-battery
  * Merge pull request #2603 from docwhat/ssh-agent-hostname
  * Merge pull request #2607 from avonderluft/dev
  * Merge pull request #2613 from Fisiu/ignore-ssh-users
  * Remove copyright information, as per #2588
  * Ignore more users in ssh completion.
  * Merge pull request #2602 from blueyed/use-default-hosts-completion-2
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh into dev
  * add option to show dirty status of current dir
  * Merge remote-tracking branch 'upstream/master'
  * Added v as a keybinding to edit-command-line
  * Merge pull request #2380 from rkh/chruby-gallois
  * Merge pull request #2435 from tompelka/master
  * Merge pull request #2466 from jarus/steeef-virtualenv-fix
  * Merge pull request #2588 from kerimdzhanov/remote-themes-copyright-info
  * Merge pull request #2584 from joukojo/master
  * Merge pull request #2590 from zhouhua015/master
  * Merge pull request #2593 from bobmaerten/typo-docker-plugin
  * Merge pull request #2591 from kevinxucs/remove-extra-aliases
  * ssh-agent: prevent environment file from flapping
  * Fixing a few quirks in the latest installer updates (quoting /Users/robbyrussell/.oh-my-zsh and such). Also mentioining our twitter account after install
  * Use zsh's default for ':completion:*:hosts'
  * Merge pull request #2149 from cristim/master
  * Merge pull request #1355 from F30/key-bindings
  * Merge pull request #2072 from jorge-d/master
  * Merge pull request #2595 from ksamdev/git.io
  * Merge pull request #2421 from LFDM/rails_plugin_fix
  * Merge pull request #2518 from erawk/master
  * Merge pull request #2326 from zakkak/master
  * Merge pull request #1776 from ronshapiro/master
  * Merge pull request #1501 from gambhiro/master
  * Merge pull request #1085 from avit/install-path
  * Merge pull request #650 from tristan0x/emacs
  * Merge pull request #2600 from jontewks/patch-1
  * Update license year
  * Updating README to show the new install URL, which redirects to the raw files on github.
  * Merge pull request #2596 from ryanwmarsh/fixing_bureau_scrollback
  * List pkgs by size
  * Fixes #2467 tab completion scrolls back in terminal when using bureau theme
  * Add github url shortener
  * Fix typo in autocomplete arguments
  * Removed unsolicited aliases.
  * Fix hgsl alias.
  * Merge pull request #2341 from mcornella/title_backticks
  * Document alternate install paths via ZSH variable
  * Abort installer on errors
  * Write install path into .zshrc
  * Reference default install path from ZSH variable
  * Remove all copyright information in themes. Closes #2587
  * Merge pull request #2331 from posva/catimg
  * Merge pull request #2479 from mrbfrank/theme-agnoster
  * Merge pull request #1402 from sergeylukin/master
  * Merge pull request #2565 from theallegedjosh/master
  * Merge pull request #2579 from mfaerevaag/master
  * Merge pull request #2535 from IgorTimoshenko/feature/yii-plugin
  * Merge pull request #2556 from chrisjones-brack3t/fix/git-prompt-1-9
  * Merge pull request #2572 from kevinxucs/sublime-linux-fix
  * Merge pull request #2059 from felipec/fc/gitfast
  * Merge pull request #2529 from emanuelez/patch-1
  * Merge pull request #2525 from lukesteensen/update-go-plugin
  * Merge pull request #2481 from felds/master
  * Merge pull request #2366 from chuancong/patch-1
  * Merge pull request #2322 from dpsk/patch-2
  * Merge pull request #2166 from cap10morgan/no-clobber-rbenv-root
  * Merge pull request #2564 from miry/patch-3
  * Merge pull request #2287 from rumpelsepp/master
  * Merge pull request #2400 from bric3/svn_fast_plugin
  * Merge conflicts with af-magic theme
  * Cleaning up conflict with merge of #2330
  * added mvnjetty alias
  * added aliases for tomcat:run tomcat7:run
  * added mvn-update
  * Updated wd plugin to v0.3.0
  * Added dirhistory plugin.
  * Integrate changes from #1841.
  * added the linux implementation to the battery plugin
  * Fixed sublime plugin behaviors.
  * :panda_face: Added simulator alias for Xcode plugin
  * adding support for node
  * gem push alias and gem yank alias
  * add gem push alias
  * add gem build alias
  * Adds command line aliases useful for dealing with JSON
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * ..a fundamental piece of matter.
  * Merge pull request #2548 from puffnfresh/gitignore-plugin-url
  * Merge pull request #2544 from fduch2k/patch-1
  * Verification of convert inside the function
  * grab last item in list which is the branch instead of relying on position.
  * Much needed PEP8 love. Use spaces, not tabs.
  * Avoid 'title:parse error' with single quotes in $CMD Fixes #2182
  * Revert previous commit, escape %
  * Use single quotes also in $LINE definiton
  * Avoid evaluating special chars in $LINE on title command (fixes #2234)
  * Adieu l'ami.
  * Merge pull request #2541 from puffnfresh/cabal-sandboxes-info
  * Remove mailcatcher from the bundler plugin.
  * Fix remaining broken URL in gitignore function
  * Update gitignore.plugin.zsh
  * Merge pull request #2542 from puffnfresh/gitignore-plugin-url
  * Fix URL to gi (gitignore) function
  * Add cabal_sandbox_info function
  * Update battery plugin to show calculating - OSX
  * Added Yii basic command completion
  * Add rake-fast plugin for fast rake autocompletion
  * Improve oneline logs
  * update golang plugin to match official version
  * remove duplicate 'go' plugin, symlink to 'golang'
  * Updated _brew zsh autocompletion to latest Homebrew upstream
  * Merge pull request #2515 from nupfel/plugins/iwhois
  * Merge pull request #2516 from lukesteensen/patch-1
  * Add 'services' command to homebrew completion
  * provides iwhois command to use CNAMES under whois.geek.nz to find most accurate whois server
  * Add scd plugin for smart change of directory.
  * Merge pull request #2465 from klange/master
  * Merge pull request #2342 from blackjid/master
  * Merge pull request #2402 from bric3/battery_level_gauge
  * highlight the username when root
  * theme agnoster: remove trailing space
  * corrected branch character
  * Merge pull request #2368 from lumbric/master
  * updated url to latest powerline-patched fonts
  * Improve virtualenv prompt in steeef theme
  * Update nyan.plugin.zsh
  * change nyancat telnet server
  * Adds a method that print a battery gauge
  * Add Laravel4 plugin
  * Adding commit hash to branch name in my favorit rjk-repos theme.
  * Fixes _rails_command
  * Renames main plugin function to `svn_prompt_info`
  * Renamed the methods of this script
  * Added further cleanup and svn status information
  * No need to eval in rvm_prompt_info!
  * Heavy refactor of svn-fast-info
  * Merge pull request #2389 from driver2000/patch-1
  * Merge pull request #2398 from phstc/fixes-tmuxinator-plugin-find
  * Inline `parse_svn` to avoid leaky state
  * Report the SVN need upgrade
  * Fixes RPROMPT in af-magic.zsh-theme
  * Renames the file to prompt_info_functions.zsh
  * Adds documentation.
  * Adds all other dummy implementations.
  * new faster SVN plugin
  * Fixes tmuxinator plugin find on OSX
  * add brew-cask plugin
  * Merge pull request #2396 from soluwalana/master
  * escape dashes
  * Update git.plugin.zsh
  * Updates spectrum.zsh
  * Fix bad right prompt placing.
  * Refactors ruby_prompts.zsh
  * Joins ruby prompt files and adds ruby_prompt_info.
  * Adds chruby_prompt_info dummy function.
  * Returns false when rbenv is not found.
  * Returns false when rvm is not found.
  * Fixes rvm_prompt_info() in lib/rvm.zsh
  * add chruby info to gallois theme
  * fix name schema for sudo plugin
  * Add support to command "show"
  * Revert "Cancel update if the current user doesn't have write permissions for the oh-my-zsh directory."
  * Merge pull request #2358 from n-st/master
  * Cancel update if the current user doesn't have write permissions for the oh-my-zsh directory.
  * Prevents oh-my-zsh loading the .zshenv twice
  * Add rdmtc alias for rails plugin.
  * typo fix
  * catimg: fix exit without using source supresses errors from convert whilen converting, as they are usually just warnings
  * Fixed a dirs bug for catimg
  * Fix for virtualenv support - fixes #2328, fixes #2297, resolves #2319
  * catimg plugin allow to print an image to the stdout using convert
  * Improve comments
  * Improve comments
  * Merge pull request #2316 from BBonifield/master
  * Making auto-correction off by default
  * Merge pull request #2303 from petervanderdoes/git-flow-avh
  * Merge pull request #2296 from pstadler/master
  * Update git-flow-avh 1.7.0
  * source ~/.profile only if it exists
  * Merge pull request #2208 from onemouth/master
  * Merge pull request #2173 from jeffrey4l/venv
  * Merge pull request #2159 from pungoyal/master
  * Merge pull request #2176 from dejanlukan/spectrum
  * Merge pull request #2194 from kevinxucs/gitignore-fix
  * Merge pull request #2195 from KevinBongart/command_blacklist_for_bundler_plugin
  * Merge pull request #2215 from posva/rand-quote
  * Merge pull request #2255 from shadyproject/plugin/xcode-support
  * Merge pull request #2258 from amilaperera/master
  * Merge pull request #2262 from mfaerevaag/master
  * Merge pull request #1520 from prooftechnique/master
  * Merge pull request #1574 from adben/master
  * Merge pull request #1683 from mnme/master
  * Merge pull request #1087 from avit/install-template
  * Merge pull request #1136 from koraa/pull_req_fastfile
  * Merge pull request #1135 from koraa/pull_req_sinchar
  * Merge pull request #1134 from koraa/pull_req_helpers
  * Merge pull request #1201 from koraa/pull_req_debian
  * Merge pull request #2088 from Stibbons/gsemet_push_pep_pylint_completion
  * Merge pull request #2086 from Stibbons/gsemet_push_repo
  * Merge pull request #1883 from Stibbons/gsemet_push_source_profile_for_upgrade
  * Merge pull request #1866 from Stibbons/gsemet_push_common_aliases
  * Merge pull request #2003 from dongweiming/update-gem
  * Merge pull request #1950 from dongweiming/add-systemadmin-plugin
  * Merge pull request #1947 from dongweiming/add-sudo
  * Merge pull request #1931 from dongweiming/update-urltools
  * Merge pull request #1942 from dongweiming/update-powify
  * Merge pull request #1940 from dongweiming/update-supervisor
  * Merge pull request #1928 from dongweiming/add-hist-stamp
  * Merge pull request #1927 from dongweiming/modify
  * Merge pull request #1956 from emesix/patch-1
  * Merge pull request #2022 from Zhann/master
  * Merge pull request #2034 from kasperisager/master
  * Merge pull request #2097 from natecox/master
  * Merge pull request #2131 from stevschmid/patch-1
  * Merge pull request #1030 from solnic/master
  * Merge pull request #950 from sonicradish/master
  * Merge pull request #948 from excepttheweasel/master
  * Merge pull request #946 from rach/master
  * Merge pull request #781 from pilif/two-lined-pygmalion
  * Merge pull request #684 from masnick/master
  * Merge pull request #639 from MarcoPeraza/git_unpushed
  * Merge pull request #513 from randy909/fix-edit-cmdline
  * Merge pull request #306 from jtriley/git-prompt
  * Merge pull request #2198 from Larandar/master
  * Merge pull request #2202 from kevinxucs/themes-random
  * Merge pull request #2212 from bsiegel/bundler_bi_function
  * Merge pull request #2222 from jamesoff/fix-battery-plugin
  * Merge pull request #2229 from prubianes/master
  * Merge pull request #2236 from Isquariel/nvm
  * Merge pull request #2270 from michaelorr/slow-git-fix
  * Merge pull request #2272 from TuiKiken/master
  * Merge pull request #2292 from Atem18/master
  * Change `bi` alias to a function
  * Merge remote-tracking branch 'upstream/master'
  * Fixed lines 32, 33, 34 where one 'p' was missing in 'zypper' command.
  * Merge pull request #2290 from jtinfors/master
  * Merge pull request #2242 from sztupy/fix-mvn-color-locale
  * Merge pull request #2252 from henrique2010/master
  * Merge pull request #2254 from Atem18/master
  * Merge pull request #2286 from ych/master
  * Merge pull request #2260 from Stibbons/gsemet_push_sublime3_support2
  * Merge pull request #2285 from dhruvasagar/master
  * Merge pull request #2240 from Kriechi/master
  * Adds the hgsl alias for one-line shortlog convenience
  * Added migration notification for rails plugin
  * Merge pull request #2249 from pabrahamsson/obsd_colorls
  * Merge pull request #2275 from wjv/wjv
  * Added/modified some useful aliases.
  * Add FreeBSD support for autojump plugin
  * Added Amuse zsh theme
  * wd.plugin: Added checks, readme and completion
  * wd.plugin: Fixed nested dirs
  * Merge pull request #2261 from webframp/feature/chruby-plugin
  * Merge pull request #2259 from eddiemonge/patch-1
  * Merge pull request #2266 from ssm/plugin/pyenv
  * Merge pull request #2271 from ashleyh/master
  * Merge pull request #2273 from thibaudgg/patch-1
  * Merge pull request #2276 from christianschmidt/master
  * Update _pass to follow symlinks for completion
  * Merge remote-tracking branch 'upstream/master'
  * Use precmd hook for updating OS X proxy icon
  * Update _heroku config arguments (Heroku Client v3)
  * Add update statistics
  * fix pip plugin
  * adding a check for git config option to disable git_prompt_info() on a per repo basis
  * unified and improved Rails plugin
  * Add pyenv plugin
  * Add simple plugin for chruby ruby version manager
  * Add support for sublime 3
  * standardize logic blocks
  * Merge pull request #2084 from mekanics/update-pod-plugin
  * Merge pull request #2253 from eddiemonge/patch-1
  * Merge pull request #2209 from quodlibetor/pip-caching-fixes
  * Merge pull request #2257 from mfaerevaag/master
  * Added wd plugin
  * Rebranded plugin according to Zypper's official alias
  * no tabs in a space-d file
  * basic command line xcode functionality
  * add aliases to readme
  * add new alias to zeus
  * Add support for colored ls output on OpenBSD
  * Merge pull request #2219 from Profpatsch/theme-agnoster
  * Merge pull request #2244 from marcoccchan/master
  * Merge pull request #2218 from wari/linuxonly-rename
  * Merge pull request #2239 from santagada/master
  * Merge pull request #2243 from sabarishcrri/bundle_plugin_nobundle_fix
  * Merge pull request #2245 from cadusk/p3
  * python3 clean updated.
  * getting the projects name correctly and making compdef to work with mux alias
  * Use environment specific open command when creating a new Jira issue.
  * bundle plugin throwing error when bundle is not in path while initializing
  * Fix issues with special characters when running mvn
  * agnoster theme not showing virtualenv status
  * Added the Bureau theme
  * Added nvm.zsh to detect current Node.js version
  * Modification to the frisk theme to work with the BZR lib
  * Modification to the frisk theme to work with the BZR lib
  * Prevent errors in prompts if no info available. Define empty functions instead of none at all if we can't figure out the platform.
  * Merge pull request #2220 from nishigori/fix-bad-ps-syntax
  * Fix bad ps syntax in ssh-agent plugin
  * Forgot one symbol for hg.
  * Merge pull request #1529 from aquaplanet/fix-sshagent-openbsd
  * `linuxonly` doesn't work unless renamed properly
  * Merge pull request #2174 from oxnz/master
  * randquote plugin correcting an issue about encoding some people was having added a message when the user doesn't have curl added varibles for colors->easier to customize
  * Make the pip cache work with djangopypi2
  * pip: successfully cache all the packages
  * Update git.plugin.zsh
  * updated to the latest version of cocoapods 0.27.1
  * themes plugin now picks a random theme if no argument is provided.
  * Add "options" as a valide 1st argument
  * Add configuration placeholders to installer template
  * Re-add whitespace
  * Add command blacklist support to bundler plugin
  * Minor gitignore fix.
  * Merge pull request #1688 from mbauhardt/z
  * Merge pull request #2138 from Profpatsch/theme-agnoster
  * Merge pull request #2165 from kevinxucs/custom-gitignore-fix
  * Merge pull request #1963 from shajra/pr/gpg-fix
  * Merge pull request #2078 from tbuehl/master
  * Merge pull request #2192 from kevintraver/tmux-aliases
  * Merge pull request #2184 from jmagnusson/agnoster_respect_venv_disable_prompt
  * Merge pull request #2107 from maxd/master
  * Add tmux aliases
  * Fix: Agnoster theme added venv name even if disabled See http://www.virtualenv.org/en/latest/index.html\?highlight\=virtual_env_disable_prompt\#activate-script for info regarding this.
  * Added the spectrum_bls function, which prints all 256 colors set as the background.
  * add itunes function to control itnues from the terminal
  * Add support .venv folder as virtual env
  * don't clobber existing RBENV_ROOT & follow Homebrew's default behavior
  * Moved misplaced plugins.
  * gitignore fix for custom folder.
  * removing a github redirect during install
  * Added a completion plugin for the new aws-cli tool
  * Merge pull request #2132 from jkaving/forklift2
  * Merge pull request #2139 from deiga/patch-1
  * Merge pull request #2145 from futjikato/master
  * Updated completion to work with comma seperated list
  * Added gitignore plugin ( for gitignore.io )
  * Added '.jar'
  * Added '.war' extension to unzip
  * More expressive symbols for git and mercurial.
  * Add support for ForkLift 2 to the ForkLift plugin
  * Fix work_in_progress in empty git repos
  * Check bundler version to avoid error with unsupported command line arguments
  * Revert "Replace no unicode glyph on hexa string"
  * Merge pull request #2065 from prudprud/master
  * Merge pull request #1763 from jonilicious/master
  * Merge pull request #1967 from tchaudhri/gdc_git_alias
  * Merge pull request #2079 from paulmelnikow/subl
  * Merge pull request #2077 from paulmelnikow/nvm
  * Merge pull request #2060 from dchusovitin/bug-node-doc
  * Merge pull request #2066 from agronemann/patch-1
  * Merge pull request #2087 from Stibbons/gsemet_push_theme_chooser
  * Merge pull request #2098 from monstermunchkin/master
  * Merge pull request #2043 from quodlibetor/fix-pip
  * Merge pull request #2053 from fluxrad/mosh
  * Merge pull request #2093 from zdevex/fixCommentsInTemplate
  * Merge pull request #2099 from mchaisse/master
  * Merge pull request #1840 from yleo77/master
  * Merge remote-tracking branch 'robbyrussell/master'
  * Added WIP alert to the gallois' theme
  * Added WIP (work in progress) feature to git.plugin
  * jump plugin: fix autocompletion with single mark
  * Added virtualenv plugin data to af-magic theme.
  * Fixed comments in zshrc.zsh-template about disabling auto updates.
  * Merge pull request #1987 from zvirusz/patch-1
  * Merge pull request #2002 from stibinator/master
  * Merge pull request #1829 from docwhat/compinit
  * Merge pull request #839 from eproxus/sunrise-fixes
  * Merge pull request #2080 from Mehonoshin/bundler-parallel-installing
  * Merge pull request #1975 from fff/master
  * repo list search one level deeper
  * Completion for python, pep8, autopep8 and pylint
  * Display right prompt in theme chooser
  * New aliases for repo plugin
  * typo
  * updated the arguments list to the newest version (0.24.0) of cocoapods
  * Logo draft 1...
  * Merge pull request #2045 from jeroenjanssens/master
  * Fix aliasing pwd
  * Mark function asks for confirmation and uses basename of directory when no argument is given
  * Change marks function and remove 'function' keyword as suggested by pielgrzym in https://github.com/robbyrussell/oh-my-zsh/pull/2045#issuecomment-22820224
  * Add _completemarks function as suggested by pielgrzym in https://github.com/robbyrussell/oh-my-zsh/pull/2045#issuecomment-22826540
  * Merge pull request #2 from JustinAiken/feature/marks_autocomplete_avaiable
  * Support of parallel bundle install
  * Better filename matching
  * Filter out missing links with jump autocomplete
  * Sublime Text: Harmonize alias with the Sublime Text install instructions
  * NVM: Avoid providing completions when nvm is not installed
  * Add commonly used git stash aliases
  * Plugin for Node Version Manager
  * Add completion for package add and remove
  * Add autocompletion plugin for meteor command
  * Update bundler.plugin.zsh
  * Replace no unicode glyph on hexa string
  * Merge remote-tracking branch 'robbyrussell/master'
  * Fixed opening documentation on Linux (node)
  * gitfast: update to upstream v1.8.4
  * Add support for mosh (remote-shell) tab completion.
  * Add tab completion for jump plugin
  * Add jump plugin, which allows you to easily jump around the file system
  * Improve pip plugin options support
  * changed duck to ddg for alias
  * Merge pull request #2028 from AeonAxan/master
  * Merge pull request #1672 from miry/rails3_command_fix
  * Merge pull request #1790 from simlegate/master
  * Merge pull request #1961 from brenttheisen/issue_1952_pr
  * Merge pull request #1960 from mekanics/plugin-pod
  * Add Pure theme
  * Merge branch 'master' of https://github.com/AeonAxan/oh-my-zsh
  * fixed minor errors
  * Update README.md
  * add docker autocomplete plugin
  * Updates Zhann theme
  * added duckduckgo to web-search
  * added duckduckgo to web-search
  * Added completion for second argument for 'brew reinstall'
  * Merge pull request #1988 from jwarwick/mix
  * Merge pull request #1992 from jeromemacias/patch-1
  * Merge pull request #1994 from kennethgeerts/master
  * Merge pull request #1993 from zvirusz/patch-2
  * Updated gem plugin zsh completion (gem 2.0.3).
  * In capistrano completion show also tasks without description
  * Fix symfony command completion 'permission denied'
  * Added autocompletion support for Elixir mix command
  * Added 'reinstall' command to brew completion
  * Merge pull request #1980 from awidegreen/upstream
  * Merge pull request #1981 from trobrock/knife-ssh
  * No cat, and hide errors for missing cache file
  * Add knife_ssh command to make connecting to servers managed with chef easier
  * Fix ssh-agent plugin identities comment for using multiple identities.
  * set default value `--max-count=10`
  * Merge remote-tracking branch 'robbyrussell/master'
  * PLUGIN: gpg-agent: export SSH_* environment variables too
  * show file liste on 'pod push [REPO]' and tab, 'pod spec lint' and 'pod podfile-info'
  * fixed typo in tmux plugin
  * Added a 'git diff --cached' alias -> 'gdc'
  * fix gpg-agent "running already" check
  * Copy and paste of two functions from Ubuntu 13.04's version of /usr/share/zsh/functions/Completion/Unix/_git that were referenced in 46f0d8d. Fixes #1952.
  * correct filename in the comments
  * Merge pull request #1935 from mateitrusca/master
  * supplemented with options
  * Update jonathan.zsh-theme
  * Add a plugin for systemadmin ops and developer
  * show repos on pod push
  * pod-list
  * commands and subcommands
  * first few lines for the autocompletion of cocoapods
  * Add sudo plugin
  * Update powify for displayed parameter is not enough, and when there is no directory error
  * Add version option
  * fixed typo in tmux plugin
  * Add shell built method
  * Add option for show in the command execution time stamp in the history
  * Modify determine the oh-my-zsh installed in non-default path of the installed
  * Update gem completion
  * Merge pull request #1764 from johnjohndoe/feature/rails3-autocompletion
  * Merge pull request #1920 from dongweiming/update-coffee
  * Merge pull request #1916 from okuramasafumi/master
  * Merge pull request #1919 from dongweiming/breaking-change-bower
  * Merge pull request #1917 from brandonblack/rvm-plugin
  * Update coffee completion
  * The current version of bower is completely unavailable, plugin depth modification
  * rvm plugin: update to ruby version helpers and rvm-update
  * Change duplicated alias name
  * Add autocompletion for Rails3.
  * Merge pull request #1913 from chriskrycho/patch-2
  * Add more capable hg incoming and outgoing count handling
  * Merge pull request #1859 from ayushs/plugin-git-clean
  * Merge pull request #1864 from Stibbons/gsemet_push_git_plugin
  * Merge pull request #1865 from Stibbons/gsemet_push_repo_plugin
  * Merge pull request #1867 from telser/master
  * Merge pull request #1869 from lucasuyezu/env_logs
  * Merge pull request #1868 from mlacorte/master
  * Merge pull request #1880 from posva/rand-quote
  * Merge pull request #1876 from chriskrycho/patch-1
  * Merge pull request #1881 from iammichiel/patch-1
  * Merge pull request #1886 from tresni/patch-5
  * Merge pull request #1901 from geecu/autocomplete_required
  * Merge pull request #1708 from tessi/extend_mercurial_plugin
  * Merge pull request #1773 from essembeh/master
  * Merge pull request #1903 from andschwa/tmux_iterm2
  * Merge pull request #1904 from oohlaf/gpg-agent-fix
  * Merge pull request #1908 from UncleBill/patch-1
  * Merge pull request #1909 from gonghao/master
  * Merge pull request #1910 from dongweiming/add-celery-completion
  * Add celery completion
  * add virtualenv prompt support for agnoster theme
  * git-pull add --rebase option
  * Typo
  * Prevent starting multiple gpg-agents
  * Not loading home tmux confs when iTerm2 tmux integration is enabled
  * Adding support for iTerm2 tmux integration via option '-CC'
  * Merge pull request #1872 from gdetrez/new-powerline-range
  * Merge pull request #1873 from charlesjohnson/bundler-plugin
  * Merge pull request #1887 from tgkokk/git-slow-fix
  * Merge pull request #1889 from jerolimov/patch-1
  * remove unused function
  * autocomplete required packages as second argumet
  * Merge pull request #1756 from rkj/master
  * Merge pull request #1885 from eakret/termsupport-fix
  * Merge pull request #1894 from codewhale/master
  * Merge pull request #1893 from jeremydt/postgres
  * debian plugin: ignore alias in sudo/aptitude check
  * Add new plugin for homebrew installed version of postgres
  * Do not clear tab when calling it with an argument.
  * Merge pull request #1877 from spazm/virtualenvwrapper-cleanup
  * Merge pull request #1878 from spazm/virtualenv-cleanup
  * Correctly detect Rapid Board
  * Fixed slow behavior when using GitHub wrappers
  * Better super-grep
  * Escape both % and $ in the command line
  * New plugin 'common-aliases' for optional cutting edge zsh aliases
  * source ~/.profile for upgrading (to source the proxy configuration)
  * Adding a rebase option to git alias.
  * Messed up the comment somehow...
  * Random quotes from the internet
  * virtualenv cleanup: replaces subshell with prompt expansion.
  * virtualenvwrapper plugin cleanup
  * Add count for incoming and outgoing changesets.
  * Merge pull request #1870 from mfrobben/patch-1
  * Update bundler.plugin.zsh
  * Update bundler.plugin.zsh
  * Update the character used in powerline
  * Update README.textile
  * add some alias for git flow
  * Adding testlog and prodlog.
  * Fixed color on git prompt for superjarin theme
  * A cabal plugin based on the lein plugin
  * Improvement in the git plugin
  * New plugin for git-repo (https://code.google.com/p/git-repo/)
  * Added alias for git clean
  * Merge pull request #1849 from lemieux/master
  * fix the open command in linux using xdg-open
  * Merge pull request #1834 from croach/disable_untracked_files_dirty_fix
  * Merge pull request #1775 from marcusmueller/fixupgradetool
  * add gf alias for git flow
  * Merge pull request #1837 from xuhdev/web-search
  * Merge pull request #1839 from Kronuz/patch-1
  * Fixed recursion. Git not needed for it to work.
  * Add web-search plugin.
  * Adding a fix for the DISABLE_UNTRACKED_FILES_DIRTY option.
  * Create the zcompdump based on version and host
  * add search by filename and file content feature
  * Merge pull request #1803 from bebugz/patch-1
  * gentoo linux support
  * add git alias 'gcmsg' and stand for 'git commit -m'
  * add git alias 'gcmsg' and stand for 'git commit -m'
  * rename gcm to gcmsg and stand for 'git commit -m' #1790
  * rename gcm to gcmsg and stand for 'git commit -m'
  * rm alias gcm='git checkout master' and add alias gcm='git commit -m'
  * Merge pull request #1774 from kevinxucs/sublime-default-2
  * Merge pull request #1779 from lorn/fasd_update
  * Cache for fasd --init
  * plugged_in function
  * eliminated unnecessary cd and failing substitution
  * Change sublime text path select priority on mac.
  * Uncomment l alias
  * Update the wrong variable used in rb20 function. Fixes #1762
  * Fixed missing retcode function
  * extend mercurial plugin to be more like git/svn
  * Merge pull request #690 from essembeh/master
  * Merge pull request #1254 from systemfreund/master
  * Spin to bundler
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Resolving conflict with merge of #1058
  * Merge pull request #1633 from alec-c4/master
  * Merge pull request #917 from agate/patch-1
  * Merge pull request #1091 from jmazzi/patch-1
  * Merge pull request #1102 from drnic/git-config
  * Merge pull request #1225 from bobmaerten/patch-1
  * Merge pull request #711 from jasongill/textmate-plugin-improvement
  * Merge pull request #424 from hackedy/fix
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Resolving conflict when merging in #528
  * Merge pull request #922 from sbfaulkner/master
  * Merge pull request #1053 from cwoodcox/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Updating the README file
  * Merge pull request #1088 from avit/avit-theme
  * Merge pull request #818 from jmacdonald/master
  * Merge pull request #1569 from ZeroKnight/master
  * Resolving conflict with merge of #970
  * Merge pull request #1223 from bigjust/master
  * Merge pull request #1620 from hreese/gpg-agent_with_sensible_ssh-agent
  * Merge pull request #1490 from khrt/master
  * Merge pull request #1565 from serdardalgic/autoenv-plugin
  * Resolving conflict in #1266 merge
  * Resolving conflict when merging in 1570
  * Merge pull request #1575 from mguindin/agnoster-change
  * Merge pull request #1582 from To1ne/pushdminus
  * Merge pull request #1608 from swanandp/m_lion_terminal_same_tab_support
  * Merge pull request #1622 from hacfi/patch-1
  * Merge pull request #1634 from Anahkiasen/patch-1
  * Merge pull request #1641 from NeuralSandwich/master
  * Merge pull request #1702 from mbauhardt/copyfile
  * Merge pull request #1715 from dbohdan/master
  * Merge pull request #1724 from miry/rails_aliases
  * Merge pull request #1703 from marcparadise/mp/knife-chef-11-initial-support
  * Merge pull request #1704 from laggyluke/st3
  * Merge pull request #1718 from toctan/master
  * Merge pull request #1721 from z2v/hgplugin
  * Merge pull request #1707 from bkg/django-static
  * Merge pull request #1714 from f0y/07738ea86330b7b77127fc6f18474b3da2c6ecec
  * Merge pull request #1719 from MatthR3D/master
  * Merge pull request #1726 from rkj/master
  * Merge pull request #1728 from szines/patch-1
  * Merge pull request #1729 from statschner/master
  * Merge pull request #1739 from felipec/fc/gitfast
  * Merge pull request #1749 from johnjohndoe/feature/zeus-auto-completion
  * Merge pull request #1733 from jaseg/patch-1
  * Merge pull request #1734 from cborgia/master
  * Merge pull request #1737 from hron84/feature-bundler-add-cleanup
  * Merge pull request #1738 from ronshapiro/master
  * Merge pull request #1748 from tobiassjosten/patch-1
  * Merge pull request #1740 from felipec/fc/git
  * Merge pull request #1750 from JamesFerguson/master
  * Only trim remote names; be git-flow friendly
  * Update rails4.plugin.zsh
  * Add auto-completion for zeus.
  * Added 'jekyll' to list of bundled commands
  * Merge pull request #1745 from jtheoof/master
  * Merge pull request #1747 from dhemmerling/mvn_tomcat-redeploy
  * mvn plugin was missing "redeploy" completion for tomcat.
  * Added option to allow untracked files as non dirty
  * gitfast: fix prompt
  * gitfast: synchronize with upstream
  * git: fix parse_git_dirty()
  * Separate the battery_pct_remaining data into it's own function so that it can be obtained even if the battery is connected.
  * Adding undocumented clean command to completion
  * Edited Grammar in template file
  * The safe-paste plugin now works with tmux, too
  * Added git-flow-avh plugin.
  * Update rvm.plugin.zsh to the latest ruby versions
  * Return code instead of dollar sign
  * Added global aliases to use RAILS_ENV.
  * Edit some yaourt aliases and add some
  * command-not-found support for Arch Linux
  * Implemented UTF-8 support in fishy.zsh-theme.
  * Add colorize plugin
  * Merge pull request #1526 from filipechagas/master
  * Merge pull request #1531 from lcosmin/master
  * Merge pull request #1532 from ryanneufeld/torrent_tools
  * Merge pull request #1537 from everbird/master
  * Merge pull request #1540 from goofansu/add-rebar-plugin
  * Merge pull request #1651 from deepusudhakar/master
  * Merge pull request #1696 from henryyan/master
  * Merge pull request #1700 from Bercio/master
  * Merge pull request #1701 from mbauhardt/copydir
  * Merge pull request #1706 from keyvez/master
  * Merge pull request #1711 from bertabus/master
  * Added Vundle clean to remove bundles removed from vimrc
  * Support for Sublime Text 3
  * Use completions with django-admin.py
  * Add collectstatic to django command completions
  * Escape spaces in folder name so script won't fail
  * Add alias for 'hg bookmarks'
  *  initial support for chef 11 integrated knife-essentials
  * a plugin (function) which copies the content of a file into the clipboard
  * a plugin (function) which copies the current directory into the clipboard
  * Merge pull request #1699 from Bercio/patch-1
  * Merge pull request #1689 from afh/pull/emoji_clock
  * >! doesn't work with no clobber, echo is redundant. Fixed all.
  * "$PWD" = "PWD", >! doesn't work, echo is redundant. Fixed all.
  * Add emoji-clock plugin
  * Merge pull request #1208 from jaischeema/master
  * Merge pull request #1060 from danielbayerlein/new-theme-inspired-by-peepcode
  * Merge pull request #729 from doitian/plugin_tmuxinator
  * 005d967dc4e879f304607a706ccd18886e630dc1
  * Merge pull request #1632 from jmatth/tmux_plugin
  * Merge pull request #1652 from z2v/master
  * Merge pull request #1654 from bertag/parse-git-dirty-support-for-1.6
  * Merge pull request #1655 from nubs/phing-and-cache-files
  * Merge pull request #1656 from hacfi/patch-2
  * Merge pull request #1665 from bmcorser/patch-1
  * Merge pull request #1679 from KokaKiwi/master
  * Merge pull request #1680 from zbrox/master
  * Merge pull request #1681 from akre54/add-bower
  * Merge pull request #1685 from justinclayton/patch-1
  * Merge pull request #1686 from timsly/hub-autocomplete
  * Merge pull request #1690 from docwhat/git-untracked
  * Merge pull request #1662 from rylwin/patch-1
  * Merge pull request #1674 from simeonwillbanks/master
  * Merge pull request #1678 from lesmyrmidons/symfony2
  * Merge pull request #1682 from maplebed/ben.knife
  * Merge pull request #1691 from gianu/master
  * Merge pull request #1697 from dsx/sublime-plugin-fix
  * Merge pull request #1698 from ConradIrwin/safe-paste
  * +safe-paste plugin
  * Prevents echo of _sublime_darwin_paths contents
  * Added $PATH to PATH in install shell
  * Removed colors from parenthesis.
  * New theme: Gianu Theme
  * This fixes checking for git untracked items
  * ohmyzsh plugin of the z project: https://github.com/rupa/z
  * added hub autocomplete instructions
  * Update _vagrant
  * use hostname instead of hostname -s
  * adding docs about knife path config variables
  * allowing you to override knife paths
  * fix some references from npm --> bower.
  * add bower autocompletion
  * Powify autocomplete
  * Add 'kiwi' theme
  * Add colored man plugin.
  * modify alias sfc => sf
  * Simplification name aliases and adding new alias
  * Fixes #1485 zeus should not be bundled
  * Mercurial: add alias for pull with rebasing
  * Merge pull request #749 from blueyed/setopt-correct
  * Merge pull request #1657 from ysmood/master
  * Merge pull request #1658 from kavu/patch-1
  * Merge pull request #1659 from AshleyS/master
  * Merge pull request #1661 from hellerbarde/master
  * Merge pull request #1558 from sbooob/master
  * Merge pull request #1573 from flz/master
  * Merge pull request #1595 from nevir/sublime3-support
  * Merge pull request #1598 from zasdfgbnm/master
  * Merge pull request #1607 from gekken/master
  * Merge pull request #1610 from mcaserta/scala_and_sbt_plugins
  * Merge pull request #1611 from ripdog/patch-1
  * Merge pull request #1614 from miklos-martin/bower
  * Merge pull request #1616 from sxeraverx/master
  * Merge pull request #1524 from bonifaido/master
  * Merge pull request #1638 from RomainBelorgey/master
  * Merge pull request #1650 from ishtu/master
  * Merge pull request #1663 from flavius/master
  * Merge pull request #1664 from marcel-wolf/master
  * Merge pull request #1668 from sheerun/patch-1
  * Merge pull request #1669 from desimone/master
  * Merge pull request #1671 from lifinsky/master
  * Exporting path to fixed config as a global variable.
  * Prefixing tmux wrapper function with '_'.
  * IMPROVED: untracked file status has priority over modified (ie: if you have both modified and untracked files, your prompt will be red indicating the presence of untracked files)
  * Use new style of rails command.
  * Fix grails plugin
  * Added golang completion support from golang.org
  * Use --no-rehash option for faster startup
  * Alias for commit and commit all with amend
  * add ssh-agent option to set default lifetime of identities
  * allow setting a custom HISTFILE before oh-my-zsh is loaded
  * Fix whitespace
  * last-working-dir: Use >! to overwrite $cache_file
  * fix git_prompt_status() to not say the repository has untracked files all the time
  * Modified to use full parameter as newer versions of base64 uses lowercase D
  * Fix git dirty status in dallas.zsh-theme
  * opt: Optimize the color scheme. Add some basic comments.
  * Autocomplete composer default methods if composer.json is not available
  * Allow ":" and "-" characters in phing tasks.
  * Use [ -nt ] instead of stat -f%m to check cache files.
  * Merge remote-tracking branch 'upstream/master'
  * add: A new theme 'ys'.
  * Tweaked parse_git_dirty() in lib/git.zsh to support proper dirty/clean parsing against both git 1.6 and git 1.7+
  * Mercurial: add aliases for 'incoming' and 'outgoing' commands
  * Escape /Users/desudhak/.oh-my-zsh path (previously broke spaces in path)
  * add function vncviwer
  * Merge pull request #1645 from mbologna/master
  * added comment for auto-generated hostname color
  * added michelebologna theme
  * Updated battery plugin.  Displays charging time.
  * Update _capistrano
  * Add alias for "composer dump-autoload"
  * Added rails4 plugin
  * Checking to make sure tmux is actually installed before running plugin.
  * Adding options to choose tmux TERM for 256 and non-256 color terminals.
  * Adding compdef to maintain tmux completions.
  * Fixing typo in alias.
  * Adding option to prevent autostarting tmux more than once in the same session.
  * Checking if already in tmux before autostarting in tmux in tmux plugin.
  * Checking environment instead of local variable for fixing term in tmux plugin.
  * Fixing typos, logic, and gremlins in tmux plugin.
  * Adding helper tmux config files to tmux plugin.
  * Enabling autostart of tmux in tmux plugin.
  * Adding comments to tmux plugin.
  * Tmux plugin now just runs tmux if any extra args are given.
  * Now checking for 256 color terminal in tmux plugin.
  * Adding main function and alias to tmux plugin.
  * Starting tmux plugin with basic config variables.
  * Fix Symfony2 command completion 'permission denied'
  * Added --quiet to suppress message about gpg-agent already running.
  * Disable ssh-agent support if another ssh-agent is already running.
  * pipe git version check error to /dev/null (for when git doesn't exist)
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Update plugins/extract/extract.plugin.zsh
  * SBT and Scala plugins.
  * Support for opening tabs and windows in the same This fixed #1498 for me on Mountain Lion
  * Update plugins/rvm/rvm.plugin.zsh
  * Did a full circle and went back to # On branch master # Changes to be committed: #   (use "git reset HEAD <file>..." to unstage) # #	modified:   git.zsh #, ignoring untracked files, which seems to be the primary cause for slowness
  * Fixed dirty check to include files added to index
  * new plugin: start fbterm automatically in /dev/tty*
  * Merge remote-tracking branch 'upstream/master'
  * Merge pull request #1594 from jbhannah/rbenv-gems-fix
  * Merge pull request #1583 from To1ne/pj.plugin
  * Support for Sublime Text 3, with fallback
  * Fix rbenv gems helper
  * Merge remote-tracking branch 'upstream/master'
  * Merge pull request #1586 from HeroicEric/master
  * add alias for rspec to zeus plugin
  * added pj.plugin
  * use pushdminus
  * [agnoster] modifying theme to show dot for dirty files and plus for staged files in git repos
  * updated adben theme: added offline content, subversion support, refactored prompt
  * Add new profiles plugin.
  * Closer to original status command, using SUBMODULE SYNTAX
  * Better custom theme loading
  * Faster dirty git status check (using git diff)
  * Add autoenv plugin, which adopts using Kenneth Reitz's autoenv into oh-my-zsh.
  * ADDED: Mercurial prompt info support even if hg prompt extension is unavailable
  * ADDED: Mercurial repository info
  * Adding MIT-LICENSE Closes #655
  * Merge pull request #1534 from gberenfield/master
  * Merge pull request #941 from dcreager/configurable-blinks-theme
  * Merge pull request #1077 from Mezzle/add-option-to-show-git-status
  * Merge pull request #1054 from ptillemans/master
  * Merge pull request #1164 from fuksito/master
  * Merge pull request #837 from stacksmashing/master
  * Update to a better fab compeletion script.
  * Add rebar to plugin
  * Merge remote-tracking branch 'upstream/master'
  * Add new plugin to autocomplete fabric commands
  * Fixed coding style
  * moved bower plugin to a separate branch
  * cleaned up
  * Fix the fix for Issue #1479
  * fix for Issue 1479
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Adding torrent tools plugin.
  * Merge pull request #1510 from agnoster/agnoster-classic
  * Merge pull request #1517 from thisiskun/master
  * Fixes #1489
  * Fixed issue with NetBSD's ls
  * added support for subversion 1.7 for svn plugin
  * OpenBSD doesn't have -ef flags for ps. Both linux and OpenBSD have -x flags which works just as greate here
  * added crcandy theme
  * Fix gitfast problem for untracket files
  * Maven plugin completion fix for other (than Java) JVM languages
  * add symbol in darcs repos to match git and mercurial
  * add unbundled command
  * Revert "agnoster theme shows error code instead of an "x""
  * git lol
  * more catspeak
  * Added `verisions` option for `homebrew` completion
  * Merge pull request #1473 from bsteuber/fix-git-flow-feature-completion
  * Merge pull request #1475 from westonplatter/master
  * Merge pull request #1477 from madsgraphics/git_prompt_showstashstate
  * Add Stash toogle to display if there's some stash or not in `git_prompt_status`
  * fixes #1474 add zeus to bundle exec listx
  * use feature names instead of failing branch names in "git flow feature"
  * Merge pull request #1084 from avit/bwana-plugin
  * Merge pull request #1133 from mappleconfusers/605ad8725b06cc15f8523404f59060b6a71bb7a2
  * Merge pull request #1139 from mappleconfusers/pull_req_git
  * Merge pull request #1233 from mugenken/knife-check-cwd
  * Merge pull request #1467 from timothyandrew/patch-1
  * Merge pull request #1468 from larrylv/unset-config-file-variable
  * Unset `config_file` variable in oh-my-zsh.sh
  * Added a `migrate` alias.
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Merge pull request #1248 from grahamc/add-symfony
  * Merge pull request #1258 from caio/git-branch-status
  * Merge pull request #778 from rschmukler/plugin-osx
  * Merge pull request #794 from markdrago/cloud_parameter
  * Merge pull request #875 from ttddyy/prompt_git-remove
  * Merge pull request #880 from darrenclark/fix-mac-terminal-app-echo-issue
  * Merge pull request #1181 from paulmars/master
  * Merge pull request #1189 from petemounce/yum-quote
  * Merge pull request #1186 from r-darwish/history
  * Merge pull request #1247 from drnic/git-cmds
  * Merge pull request #1273 from ystein/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Resolving conflict in merge of #1313
  * Merge pull request #1387 from jimhester/vi-mode-patch
  * Merge pull request #1458 from ranman/master
  * Merge pull request #1454 from gAmUssA/patch-4
  * Merge pull request #1462 from aliasbind/master
  * Merge pull request #1460 from tresni/patch-4
  * Merge pull request #1459 from tresni/patch-3
  * Merge pull request #1463 from syphar/fix_last_working_dir
  * Fix prompt color: Change it back to green
  * plugin last-working-dir: create cache-directory if it doesn't exist
  * Print last exit status in mortalscumbag prompt
  * urltools for Everyone
  * Backwards Compatible Jira URLs #1378
  * use lazy load for virtualenvwrapper
  * hg_current_branch added to mercurial plugin
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Merge pull request #1457 from NeuralSandwich/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Fixing conflict in install scripts
  * Merge pull request #1328 from mfoo/master
  * Merge pull request #1301 from bencao/master
  * Merge pull request #1293 from cenkalti/master
  * Merge pull request #1295 from XL64/master
  * Merge pull request #1298 from nickhutchinson/fishy
  * Merge pull request #1382 from fushunpoon/master
  * Merge pull request #1191 from r-darwish/themes-plugin
  * Merge pull request #1235 from henryyan/master
  * Merge pull request #1241 from agrimaldi/git-extras
  * Merge pull request #1249 from korjavin/aptitude
  * Merge pull request #1255 from SuprDewd/master
  * Merge pull request #1256 from seegno/master
  * Merge pull request #1259 from bwl/sublime-fix
  * Merge pull request #1263 from tedv/headless-git
  * Merge pull request #1265 from aletessier/ssh-completion
  * Merge pull request #1274 from sc68cal/feature/git_decorate_log
  * Merge pull request #1277 from waveface/master
  * Merge pull request #1278 from bitboxer/forklift
  * Fixed Kernel Detection in battery plugin
  * Merge pull request #1284 from obmarg/feature/debianwhichfix
  * Merge pull request #1317 from thcipriani/junkfood_theme
  * Merge pull request #1319 from skatkov/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * resolving conflict in termsupport plugin
  * Merge pull request #1336 from aelesbao/plugin-systemd
  * Merge pull request #1341 from markusscherer/master
  * Merge pull request #1354 from F30/master
  * Merge pull request #1353 from a-b/master
  * Merge pull request #1371 from rdrey/master
  * Merge pull request #1376 from javageek/master
  * Merge pull request #1375 from dsx/better-pyclean
  * Merge pull request #1378 from hjhart/master
  * Merge pull request #1453 from simonoff/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * git find
  * Merge pull request #431 from meh/rsync-plugin
  * Merge pull request #409 from Bregor/patch-1
  * Merge pull request #214 from allancaffee/master
  * Merge pull request #1455 from NeuralSandwich/master
  * Merge pull request #1456 from sputnikus/master
  * Removing mcd as it conflicts with mtools
  * Renaming cap to capistrano
  * Functions for managing pacman-key
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Added Candy-Kingdom theme
  * Merge pull request #256 from lorrin/no-op_command-not-found
  * Merge pull request #253 from loopj/master
  * Added support for Mac to battery plugin
  * Update plugins/sublime/sublime.plugin.zsh
  * Merge pull request #516 from adben/master
  * Set default for rvm prompt prefix/suffix
  * Fix RVM loading and RVM ruby version info
  * Simonoff theme
  * Merge pull request #455 from aslamnd/master
  * Merge pull request #448 from n0nick/patch-1
  * Merge pull request #1451 from rmcastil/modify_readme_to_clarify_the_manual_way
  * Merge pull request #1452 from miry/github
  * Fix repo for github.
  * Make the NOTE an optional for improved instructions
  * Improve formatting of step 2 for clarity
  * Merge pull request #1393 from agate/patch-2
  * Merge pull request #1365 from pcasaretto/add-heroku-remote-switch
  * Merge pull request #1366 from op/last-working-dir
  * Merge pull request #1370 from ericmathison/syntax-fix
  * Merge pull request #1347 from paulredmond/plugin/jira
  * Merge pull request #1386 from sanbor/master
  * Merge pull request #1390 from pluton8/bugfix/autojump21
  * Merge pull request #1435 from Drarok/fix-svn
  * Merge pull request #1421 from cristim/master
  * Merge pull request #1399 from tresni/patch-1
  * Merge pull request #1400 from tresni/patch-2
  * Merge pull request #1416 from talmuth/master
  * Merge pull request #1410 from jimhester/per-directory-history
  * Merge pull request #1411 from niceview/rvm
  * Merge pull request #1413 from arnihermann/master
  * Merge pull request #1412 from jdavis/coffee_plugin
  * Merge pull request #1418 from Mehonoshin/patch-2
  * Merge pull request #1419 from ssrihari/master
  * Merge pull request #1439 from maxbane/master
  * Merge pull request #1442 from willman500/git-hub-flow-plugin
  * Merge pull request #1445 from knxroot/master
  * Modifying documentation in zshrc template for new config option
  * Merge pull request #1430 from danielsoneg/egd-update_frequency
  * Merge pull request #1437 from Partyschaum/master
  * Merge pull request #1446 from suzaku/patch-1
  * fix typo
  * Node.js version of urltools es more fast (53% aprox), you can try this with strace -o trace -c -Ttt
  * Add autocomplete for git "hubflow"
  * fixed autojump: autocompletion works with homebrew again
  * Merge branch 'master' of github.com:Partyschaum/oh-my-zsh
  * fixed autojump plugin: works with homebrew again now
  * Revert "Fix to restore bindings after switching to vi-mode"
  * fixed symbolic-ref git view of agnoster theme
  * removed 'x' from prompt_context() function name
  * Fix the backwards svn status, and add comments explaining which way grep does things.
  * Whitespace cleanup.
  * Add UPDATE_ZSH_DAYS setting
  * Merge pull request #1426 from caarlos0/master
  * fixes my wrong commit - fixes #1423
  * Merge pull request #1391 from logicmd/master
  * Merge pull request #1388 from fuadsaud/agnoster_theme_show_exit_status
  * Merge pull request #1395 from caarlos0/master
  * Merge pull request #1406 from chinghanho/master
  * Merge pull request #1404 from Bklyn/master
  * Merge pull request #1396 from webframp/fix/brew-autojump-zsh
  * Merge pull request #1415 from jmatth/git_root_pull
  * Merge pull request #1417 from felipec/fc-git-upstream
  * Added a small mod of the tjkirch theme
  * Added alias to rake db:test:prepare
  * Added gwc(git whatchanged alias)
  * Add gifast plugin
  * e alias
  * fixing various issues with build, add runinstall option
  * fixing some build issues...
  * Add support of screen-* $TERM in screen plugin
  * fixing issue with solr in jboss start
  * go
  * param -i para gerar installer
  * oops
  * totvs utils
  * Adding grt alias to the git plugin.
  * Use pull --rebase for 'gup' shortcut.
  * Added host to prompt
  * Added sf Symfony2 binary alias
  * Added a CoffeeScript plugin.
  * Use rvm completion from ~/.rvm/scripts/zsh/Completion
  * Replace reset-prompt with push-line and accept-line
  * Improved statistics functions, effect:
  * Untabify
  * Handle metachars in svn status output using grep -q
  * Fix /bin/sh compatibility issue in install.sh
  * Update plugins/svn/svn.plugin.zsh
  * Update themes/minimal.zsh-theme
  * made dpkg -i more util
  * update autojump plugin for latest brew installed autojump
  * mvn.colors.plugin.zsh was not read... mergin with mvn.plugin.zsh.
  * Added some maven love.
  * Update plugins/git-flow/git-flow.plugin.zsh
  * Update plugins/sublime/sublime.plugin.zsh
  * Fix sourcing brew's autojump of version 21.0.3+
  * agnoster theme shows error code instead of an "x"
  * Fixes for vi-mode terminal overwriting bugs
  * Added pass plugin in order to provide completion.
  * Expand for-loop so that it works under Snow Leopard Terminal.app.
  * Update plugins/jira/jira.plugin.zsh
  * Updated code from answer URL
  * Added ability to specify list of directories for pyclean to override default current directory
  * Fixed node-docs
  * Fix color syntax
  * Added last working directory plugin
  * Add the heroku --remote switch
  * Replace hardcoded key escape sequeneces with dynamic ones from terminfo.
  * add git-extras plugin
  * Merge remote-tracking branch 'upstream/master'
  * Make sure the terminal is always in application mode when zle is active.
  * Don't clobber standard Esc+. behavior
  * forgot to save before committing. doh
  * Added documentation to key bindings.
  * Set the '-R' option for less not in $PAGER, but as $LESS.
  * updated symbol
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Something to be said for symmetry
  * spacing makes me something
  * parens tweak
  * removed weird characters
  * moved spacing
  * Wrong URL :zap:
  * Merge pull request #1344 from danielcsgomes/master
  * Merge pull request #1306 from josh-/master
  * Merge pull request #1312 from koenpunt/fixes_cap_plugin
  * Merge pull request #1330 from trobrock/hide-rvm-prompt
  * Merge pull request #1333 from b4mboo/master
  * Merge pull request #1335 from paulredmond/plugin/jira
  * Merge pull request #1346 from ianchesal/urltools
  * make README reflect latest changes
  * URL Tools Plugin
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * added a comment to the composer installation alias
  * added Composer completition and aliases
  * added two aliases to Symfony2 Plugin
  * fix title setting bug in xterm and urxvt
  * fix test aliases
  * Missing comment line
  * Added systemd plugin with aliases for systemctl commands.
  * look for test/unit instead of test/units. #typo
  * Correct error message.
  * Merge pull request #1327 from agnoster/master
  * Clean up doc
  * Jira ticket shortcut to browse existing issues or create a new issue.
  * Merge remote-tracking branch 'upstream/master'
  * Add zeus plugin
  * Make rvm prompt function a bit cleaner
  * Fixing the rvm_prompt_info command, now it will not show empty parens if no rvm is currently being used
  * Add user-local installation autojump zsh plugin source
  * Add link to gist
  * Updated documentation for agnoster theme
  * Merge pull request #1318 from trobrock/add-puma-to-bundler
  * Merge pull request #1320 from jimhester/vi-mode-patch
  * Merge pull request #1321 from jimhester/per-directory-history
  * Merge pull request #1322 from jimhester/colemak
  * Merge pull request #1323 from lxmonk/autojump-port
  * Use HISTFILE evironment variable directly rather than copying it
  * added autojump plugin support for mac os x + port
  * Red prompt for remote hosts
  * Colemak plugin
  * Per directory history plugin
  * Fix to restore bindings after switching to vi-mode
  * Last spacing adjustment...I swear
  * Modified spacing one last time
  * Replace cp verbose with rsync
  * Bundle exec puma also http://puma.io
  * modified spacing on junkfood theme
  * Added fat arrow the theme
  * Refactored theme
  * Added space to prompt
  * Added junkfood theme
  * git plugin: Add `gpoat` alias
  * Add agnoster.zsh-theme
  * fixed incorrect if/else
  * updated cap plugin to use `cap -T` instead of `cap show_tasks` which didn't exist (sometimes?)
  * Merge remote-tracking branch 'upstream/master'
  * fixed nginx vhost template, made variables local, imroved parameter validation
  * Merge remote-tracking branch 'upstream/master'
  * added lesscss plugin
  * Add new 'nanoc' plugin
  * Nuke _cap_does_task_list_need_generating
  * Rendering the 'vagrant box (remove|repackage)' completion code independant of Vagrant implementation details.
  * fix rvm auto complete, pointing to $rvm_path
  * nginx and php-fpm plugins
  * Update fishy theme to collapse working directory in PROMPT.
  * Merge pull request #1228 from clutt0n/master
  * Merge pull request #1287 from johnhamelink/master
  * Merge pull request #1279 from 3den/master
  * Merge pull request #1297 from everbird/master
  * add new plugin to autocomplete supervisor commands
  * Add empty function rbenv_prompt_info() if doesn't exists
  * search virtualenvwrapper.sh in PATH
  * Added another path for virtualenvwrapper plugin
  * Add keep branch option.
  * Added laravel plugin which gives aliases to artisan and bob, and provides autocompletion for artisan.
  * Debian plugin now pipes which stderr to stdout
  * new 3den theme with RVM and GIT
  * Merge branch 'master' of github.com:ptillemans/oh-my-zsh
  * new forklift plugin
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Add shortcut for showing log of all branches
  * fix typo in cd-wrapper
  * application completion
  * library completion
  * in hindsight, this is probably a bad idea
  * Correct variable used for global ssh known host completion
  * Make git use sha when branch name is missing.
  * completion of targets
  * instance and cluster completion
  * Add branch status support to git_prompt_status
  * Adding logic for ~/Applications folder installs of Sublime Text 2
  * Add a configuration option to disable autocorrect
  * Added a "please" alias for sudo
  * Merge branch 'master', remote-tracking branch 'rr/master'
  * Added go completion script. Taken from /misc/zsh/go
  * alias at=aptitude broke /usr/bin/at scheduler. Just an idea: change it to ap
  * Merge
  * node completion
  * delete os specific disable-patterns
  * help command, node completion
  * Adding a symfony plugin, for symfony 1
  * improvement: define PROMPT_HOST once on startup
  * added 'gcl'for 'git config --list'; and gd for 'git diff'
  * Merge pull request #1229 from seban/run_rails_without_bundle_exec
  * auto-upadate feature will now reset the epoch so that if a user doesn't say yes, it won't ask them again for a while. fixes #1240
  * Fix changelog --list completion bug
  * Added credits
  * Added git-extras completion
  * Added avit theme
  * Bwana plugin for reading man pages in Safari
  * add maven zsh autocomplete plugin, copy from juvenxu's bash maven autocomplete plugin
  * check for knife.rb in cwd
  * merge from upstream master
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * modify themes/jnrowe.zsh-theme, add host directive "Ξ (mbsd) ~ →"
  * 'rails' command should not be run with bundle exec
  * added _files values for certain options
  * completion options
  * added alias
  * added completions for all known arguments to all known commands
  * vagrant uses 'ssh-config' command, not 'ssh_config'
  * Add very basic virtualenv plugin
  * Merge pull request #1200 from andyfleming/master
  * apparently, this file must exist for the plugin to load
  * added completion for all asadmin subcommands
  * Merge pull request #1206 from Eustachy/upstream
  * Merge pull request #1216 from joshvermaire/patch-1
  * utilize sublime's embedded command line binary
  * escape whitespace
  * Merge pull request #1122 from varunkvv/master
  * Merge pull request #1127 from a-b/master
  * Merge pull request #1193 from bameda/master
  * Merge pull request #1209 from lwe/rbfu-plugin
  * Merge pull request #1170 from dipth/master
  * provide plugin for rbfu the ruby version switcher
  * Fix the rvm gemset right prompt:wq
  * Add new theme : jaischeema
  * Remove bogus "-" from nomz="ps -aux" alias.
  * Remove debug info
  * Dynamicly generate completion functions to support changing apt_pref
  * Add myself to the authors list
  * Use a static apt-get where only apt-get works
  * Add completion instructions for apt/aptitude commands
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of github.com:essembeh/oh-my-zsh
  * Comment l alias
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Merge remote-tracking branch 'upstream/master'
  * Added another path
  * Merge pull request #1190 from vpacher/master
  * Merge pull request #1192 from rcakirerk/a39c9ffe5b7236b6e4dc78efa80b478cc411af7f
  * Fix finding git issue. http://stackoverflow.com/questions/592620/check-if-a-program-exists-from-a-bash-script
  * Added completion to the theme selection plugin
  * Added themes plugin
  * added jexec
  * added plugin for jruby
  * Fix mismatched quote in yum plugin
  * Merge pull request #1174 from insside/rbenv-homebrew-fix
  * Merge pull request #1126 from natsumesou/fix-ignore-symlink
  * Merge pull request #1182 from jugyo/patch-1
  * Merge pull request #1159 from kristi/master
  * Merge pull request #1173 from walkah/virtualenvwrapper-osx-fix
  * Merge pull request #1168 from r-darwish/yum-plugin-fix
  * Added history plugin
  * correct the ruby version label for rbenv
  * add git remote branch autocomplete
  * theme cleanup
  * added first version of my theme af-magic
  * sanitized code according to coding style
  * rbenv plugin now uses 'brew --prefix rbenv' command to find rbenv folder
  * remove readlink call and clean up
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Explicitly tell rbenv to use zsh
  * Fixed unmached " in yum plugin
  * More usable and shorter aliases
  * avoid VCS folders
  * Merge pull request #977 from scialex/better-d
  * Merge pull request #980 from vmalloc/dircycle_plugin
  * Merge pull request #984 from vmalloc/less_r_pager
  * Merge pull request #985 from pomaxa/master
  * Merge pull request #999 from ChaosData/master
  * Merge pull request #1016 from fuksito/master
  * Merge pull request #1032 from r-darwish/suse
  * Merge pull request #1055 from daniellockard/patch-1
  * Merge pull request #1065 from ntpeters/patch-1
  * add --directory flag
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Updating README to ask people to stop sending themes for now
  * Merge pull request #1148 from erichmenge/git-flow-plugin
  * Merge pull request #1019 from matschaffer/patch-1
  * Use grep to detect if untracked files exist instead of storing all the output of ls-files.
  * Merge pull request #239 from fred-o/master
  * Merge pull request #1146 from westonplatter/master
  * Merge pull request #1152 from mispy/virtualenvwrapper
  * Merge pull request #1155 from s3dev/s3dev
  * Merge pull request #1145 from tjl2/master
  * Merge pull request #1156 from thackoun/master
  * fix a very minor bug with colors of parenthesis in the terminalparty theme
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Change hardcoded ~/.oh-my-zsh to $ZSH.
  * Plugin which loads Python virtualenvwrapper and activates virtualenvs on cd into git repos
  * Merge branch 'master' of github.com:westonplatter/oh-my-zsh
  * checking if airport allows git protocol
  * Merge remote branch 'upstream/master'
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Added spin to bundled_commands (Bundler plugin)
  * Add a couple of options for git-flow.
  * rails3, added rgm = 'rails generate migration'
  * Removing ey command from bundled_commands. It is not usually bundled.
  * Merge pull request #1138 from amarraja/master
  * Merge pull request #1140 from mappleconfusers/pull_req_debian
  * Now with 50% less auto-updates.
  * Add command to directly install the output of acs
  * Make the $apt_pref variable evaluatet at alias expansion by using single-quotes instad of double quotes
  * Add aliases for git-remote: gr...
  * Prevent the heroku command from being automatically bundle-exec'ed The heroku command should not be executed via bundler, see: https://github.com/heroku/heroku/issues/173
  * Enhance handleing of spaces in filenames
  * Add the fastfile plugin
  * Make (s)xf not search in current dir
  * Make grep recoursive
  * Enhance file find
  * Add Man
  * Add file finders
  * Enhance writing routines
  * env_defaul=>env_default
  * Add sudo without xargs shortcuts
  * Add pager shortcuts
  * Add download shortcuts
  * Add a description
  * Add cat (+write, +append), enhance formatting
  * Add the singlechar plugin
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Add helper to easily define default values for variables and env variables.
  * Add helper to get the value of an alias only
  * Fixed a bug in checking the platform
  * fino-time theme
  * add fasd plugin
  * Load symlink custom files
  * Add Sublime Text 2 alias for Linux.
  * Added zp and zps aliases for the SUSE plugin
  * Added suse plugins
  * Merge pull request #1026 from dir01/patch-1
  * Merge pull request #1079 from dylnhdsn/feature/sublime_text_plugin
  * Merge pull request #1105 from Drarok/fix-svn
  * Merge pull request #1111 from jimeh/fix-ZSH_CUSTOM-variable
  * Move example plugin to the custom plugins dir.
  * Load themes from `$ZSH_CUSTOM` instead of `$ZSH/custom`
  * Suppress "zsh: no matches found" error when $ZSH_CUSTOM has no files
  * Don't drop everything after a trailing slash, as this breaks standard svn branches: ^/branches/featurename ^/releases/Release-vx.y ^/trunk
  * added 'gcl'for 'git config --list'; and gd for 'git diff'
  * Fix formatting
  * Add instructions on handling updates and prompts.
  * changed the alias to use to cli provided by sublime text
  * added aliases for sublime text
  * Add option to disable status notification
  * Merge remote branch 'upstream/master'
  * Added yum aliases for: makecache, grouplist, groupinstall, and groupremove.
  * Add Theme "itchy"
  * Adds glo; glp (arg)
  * Added an if-statement to see if git is installed
  * Added subcommands for leiningen 1.7.0
  * command to restart pow process
  * small changes to make it prettier
  * add the half-life theme based on steeef and lambda
  * Added an <esc> to the begining of everything. I ran something when I was in insert mode once and all it did was shove !args... into the buffer.  <esc> first.
  * Updated the README to include documentation on the postCallVim callout
  * Added an optional callout to the end of the interaction function. I put it in to allow me to put the window focus on MacVim / GVim depending on the different OS I happen to be on
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * [themes/josh] Use $(current_branch) in prompt
  * add maven plugin
  * Python plugin: added pygrep command, simplified pyclean
  * Fixed: If you callvim on a non-existant file with a relative path, the CWD of the running gvim process is used, and that's not right.  We use the PWD explicitly instead, in this case
  * A plugin that makes it easier to interact with the (single) running instance of gvim
  * Add a cat smilie as alias for cat
  * Don't clobber standard Esc+. behavior
  * Plugin for encoding strings into base64 and decoding them
  * added powed command to list pow urls
  * delete time filed
  * Disabled title function for emacs term mode
  * fix gnzh theme to detect local rvm installations
  * change color of @ to cyan
  * add hostname behind username, example: henryyan [02:07:20]  ~/.oh-my-zsh git:(master) ✗
  * move kafeitu.zsh-theme to themes folder
  * Added kafeitu theme it modified by robbyrussell
  * Added link to wiki page for plugins to README.
  * current repository action
  * Pager is 'less -R' to support colored outputs
  * Add dircycle plugin: enables cycling through the directory stack
  * made the 'd' alias only show the directories that can be cd'ed to using the number aliases
  * Add gem build autocompletion
  * clean up rbenv support for 'fino' theme
  * merge changes from offical repo
  * Fix spurious correction with sudo vim
  * Add completion for pip install -r - so that it autocompletes requirements filenames
  * Merge pull request #958 from cruser42/master
  * Fixed bug introduced when fixing issue 896
  * Merge pull request #868 from wgriffioen/bundler_add_rails
  * Merge pull request #925 from cruser42/bugfix/gitversionfix
  * [JM] Removed LSCOLOR Declaration for Wider Support
  * Added New Theme: sonicradish  (256 colors)
  * Added a peepcode theme
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * change the color of arrow when the command line return an error
  * blinks theme works with light and dark Solarized
  * handle case where ~/.rvm/bin/rvm-prompt is not in path, so "which" can't find it
  * fixed introduced to parse_git_dirty
  * changed variable PRE_1_7_2_GIT to POST_1_7_2_GIT to make it more accurate
  * fixed asterisk display for modified repos in git prior to 1.7.2
  * add default rbenv_prompt_info implementation to close #878
  * added "publish" and "track" command completion for git-flow plugin
  * Fixed Mac OS X Terminal.app related issue with extra newlines being printed out sometimes
  * Merge pull request #666 from szetobo/rails_runner
  * Removed trailing spaces in Git files. Fixes #867
  * update rails runner alias to ru
  * prompt git-remove as deleted
  * added rails to bundled_commands
  * Merge pull request #663 from gravof/patch-1
  * Merge pull request #850 from johnantoni/pow-fix
  * Merge pull request #860 from sbfaulkner/rbenv-support-for-themes
  * Merge pull request #865 from iltempo/patch-1
  * adding engine yard command (ey) to bundler binstubs
  * adding rbenv support to all the rvm themes
  * Merge pull request #845 from tjwallace/bundler_plugin_fix
  * Merge pull request #717 from blueyed/github-plugin-working-hub
  * Merge pull request #801 from kalos/autojump
  * Merge pull request #811 from markdrago/remove_verbose_mercurial_flags
  * Merge pull request #853 from lepht/master
  * Merge pull request #810 from cseeger/master
  * Merge pull request #856 from sgharms/patch-1
  * Merge pull request #858 from tatey/bundle_plugin_middleman
  * Add middleman to bundled commands
  * Grammar update
  * Fixed compdef alias to use 'gd' as shortcut.
  * Updated to latest version of taskwarrior completions (using Taskwarrior 2.0b4)
  * bug : stop creating those ~ directories add powit command to symlink an app if it hasn't been already
  * don't check for tmp dir
  * add alias to view the standard out (puts) from any pow app
  * take in csexton's changes
  * fix for pow plugin to default to current dir
  * Merge pull request #721 from gawel/master
  * Merge pull request #783 from oteyatosys/master
  * Merge pull request #830 from dbye/speedup
  * Merge pull request #847 from msharp/master
  * added a rake plugin to disable zsh file globbing when calling rake tasks with square brackets
  * fix bundler plugin for root level folders
  * Merge pull request #840 from arbovm/master
  * Merge pull request #838 from Bounga/bundled_thor
  * Merge pull request #833 from backspace/patch-1
  * fixing #812: adding plugins w/o plugin.zsh file to fpath.
  * Correct color and font issues on Ubuntu
  * Add Thor to bundled commands
  * Removed the assignments to fpath as well, since that's all handled in the .oh-my-zsh/oh-my-zsh.sh boot script.
  * sprunge-plugin: Remove the unnecessary while loop.
  * Fix the behaviour of the sprunge plugin so that is preserves whitespaces and tabs.
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Don’t report that Oh My Zsh has been updated when it hasn’t.
  * Removed calls to compinit in the extract and the bundler plugins. compinit should only be called once, after all modules, libs, etc are imported.
  * Merge branch 'master' into cloud_parameter
  * check if autojump is installed
  * Merge pull request #784 from lnxbil/967e84ebaa180ad2ab1eebc9a512f94d93e84aea
  * Merge pull request #806 from OutPunk/terminalapp-plugin
  * Kill the compdef; Introduce 'grh' alias for 'git reset HEAD'
  * Added alias for git diff.
  * Merge pull request #816 from lucapette/add-annotate-to-bundler-commands
  * add annotate
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh into cloud_parameter
  * remove the -v flag from a few mercurial aliases
  * Git Plugin: adds 'grhh' alias for 'git reset HEAD --hard'
  * Apple Terminal.app resume directory plugin
  * autojump plugin enhanced
  * Merge pull request #785 from simonjefford/patch-1
  * Merge pull request #799 from plindborg/ruby-plugin-fix
  * Fixed the rfind command in the  ruby plugin
  * Merge pull request #790 from cicloid/master
  * add ability to set custom prefix for cloud theme
  * Get the Hostname
  * bundler plugin - don't "bundle exec rails"
  * correctly handle path names with spaces
  * multiple versions could occur and should also be highlighted
  * Mortal Scumbag Theme
  * make pygmalion theme use two lines when needed
  * Added vsplit_tab and split_tab for iTerm. Create new session within a vertical/horizontal split of the tab respectively.
  * Merge pull request #679 from ornicar/official
  * Merge pull request #671 from peterhoeg/31cddcd32427a5f5d3daa0da168d39aba5b510b4
  * Merge pull request #688 from alexstrat/master
  * Merge pull request #693 from dreur/upstream-debian-apt-history
  * Merge pull request #702 from sirech/fix-bundle-compl
  * Merge pull request #710 from moutten/patch-1
  * Merge pull request #669 from peterhoeg/f/battery
  * Merge pull request #618 from fceccon/custom-theme
  * Updating installation documentation to show a curl example as well for those who don't have wget installed.
  * Merge pull request #776 from mytechnix/master
  * Merge pull request #747 from ilikenwf/1a49f6443c0230b8e182294546ed9ef2a5110bf2
  * Merge pull request #764 from Fl4t/submodules
  * Merge pull request #772 from indrajitr/master
  * Merge pull request #765 from trevor/master
  * Merge pull request #768 from askreet/master
  * Merge pull request #769 from divineforest/master
  * Merge pull request #775 from tatey/sammy_black_on_white_theme
  * Added example aliases in ZSH template. Added a new theme.
  * Black on white theme inspired by Sam Stephenson's terminal screenshot on https://github.com/sstephenson/rbenv
  * Fix upgrade and uninstall functions to pick up $ZSH value
  * Added alias gcm='git checkout master
  * Added support for entries in /etc/ssh/ssh_known_hosts.
  * Ignore submodules dirty in prompt info
  * add note about custom plugins
  * Merge pull request #752 from andrewtch/symfony2-completion
  * Merge pull request #757 from cwjohnston/knife-environments
  * Merge pull request #759 from Zhann/master
  * show gemset next to ruby version
  * adding support for chef environments in knife plugin
  * Symfony 2 completion
  * Merge pull request #708 from eatnumber1/update-print
  * `setopt append_history` is not necessary.
  * Only `setopt correct`, not "correct_all".
  * add sprunge.us pastebin uploader - uses files, or pipes
  * Merge remote branch 'upstream/master'
  * Fixes and improves the behavior of the tm command
  * Merge pull request #343 from giddie/plugin-wakeonlan
  * Merge pull request #743 from c089/autojump-macports
  * Merge pull request #741 from suvash/master
  * Merge pull request #738 from pygatea/master
  * Merge pull request #733 from Zhann/master
  * Merge pull request #732 from ggustafsson/patch-1
  * Merge pull request #734 from maxpersson/726-pip-completion
  * Merge pull request #709 from docwhat/custom-plugin-fpath
  * Merge pull request #707 from gmcmillan/master
  * Merge pull request #706 from docwhat/termsupport-hook
  * Merge pull request #701 from kirs/master
  * Merge pull request #553 from benlumley/master
  * add support for autojump installed via macports
  * Added my own theme file : suvash
  * forks miloshadzic theme to add more directory info as well as user and host info
  * Merge remote branch 'upstream/master'
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * Added message when caching packages
  * Added caching of packages
  * Added brute force package completin on install subcommand
  * Adding critical security patch to let you all know I'm on top of this shit. add 'nyan' to your plugins... then run  for security upgrade.
  * Added Zhann theme. Based on Robbyrussel theme, but shows the current ruby version and has some color variations.
  * Removed duplicate setting and sorted the remaining
  * Jake-node plugin : update - remove the need to write a `jake_tasks` in the directory - use most recent usage of completion with zsh - tested for MacOSX and Ubuntu
  * tmuxinator completion
  * allow django-manage completion. http://pypi.python.org/pypi/DjangoDevKit
  * Only alias git=hub if `hub --version` works.
  * Update theme
  * Add the --format tag to knife list commands
  * Moved ZSH_CUSTOM declaration before fpath is set
  * set fpath correctly for custom plugins
  * Use printf rather than echo -e in update.sh
  * Added option to disable the update prompt. Set DISABLE_UPDATE_PROMPT to true to enable.
  * Added add-zsh-hook support to themes
  * lib/termsupport now uses add-zsh-hook
  * FIX: commands like ruby and rake where not being completed
  * Rails Migrations support
  * Add apt-history to debian plugin
  * Update completion for SSH
  * Adding custom theme
  * minor modifications in comment header (the revenge)
  * Minor modifications in comment-header
  * Added completion plugin for jake
  * update fino theme to work with rbenv
  * Add yaourt --sucre alias in archlinux plugin
  * Add zsh_reload which provides src function, this function will source .zshrc and rebuilds cache
  * fix: rbenv: I need to find a proper way to test changes...
  * add: rbenv plugin
  * add: battery plugin
  * add rails runner alias
  * Replace "git-diff" with "git diff" in the git plugin
  * RVM info
  * FrontCube theme with git status
  * Update the script to account for the changes in 0.1.7 where .gas is a directory
  * Do not overwrite EDITOR environment variable if already defined.
  * Comment
  * Merge remote-tracking branch 'upstream/master' into emacs
  * Fix builtin `ecd' when file path contains space characters.
  * Merge pull request #505 from masnick/master
  * Merge pull request #529 from dbb/master
  * Merge pull request #552 from Tricon/master
  * Merge pull request #579 from hakanensari/bundler-plugin-patch
  * Merge pull request #594 from sirech/fix-bundle-compl
  * Merge pull request #595 from zachriggle/grails-plugin
  * Merge pull request #554 from toolbear/549-fix-auto-upgrade
  * Merge pull request #607 from vddgil/patch-1
  * Merge pull request #613 from rkj/master
  * Merge pull request #614 from philippbosch/feature/terminitor-plugin
  * Merge pull request #622 from foozmeat/master
  * Merge pull request #626 from nickstenning/upstream
  * Merge pull request #631 from danshearmur/git-merge-alias
  * Merge pull request #645 from mr-szymanski/master
  * Merge pull request #648 from SFEley/d926a55872b5a12ab8b987e9d86c02358d0c825e
  * Merge pull request #418 from ptrv/master
  * Merge pull request #441 from Gonzih/master
  * Merge pull request #273 from blueyed/hub-alias-only-with-ruby
  * Merge pull request #225 from Soliah/plugin-bundler
  * Merge pull request #205 from sorin-ionescu/plugin-gnu-utils
  * Merge pull request #482 from volpino/master
  * Merge pull request #428 from matthewmccullough/gradleplugin
  * Merge pull request #338 from norm2782/master
  * Merge pull request #319 from sorin-ionescu/plugin-npm
  * Merge pull request #275 from tristan0x/require_tool
  * Merge pull request #274 from diofeher/master
  * Merge pull request #525 from kibs/master
  * Change default zshrc to export $ZSH (as required by check_for_upgrade.sh).
  * Fix up some wonkiness
  * Add new theme: wuffers
  * Show if you're ahead of remote in the wedisagree theme
  * added git merge as gm
  * Better cake completion: don't barf on options, and don't clobber user's namespace
  * This is the correct way to check the return value
  * This needs to explicitly check the return value
  * First search in the custom folder for the theme
  * Adding README file for the wakeonlan plugin
  * split rkj into two themes.
  * Splitting wakeonlan plugin completion into separate file
  * Forgot to quote the path parameter to wakeonlan
  * Tweaks to the wakeonlan plugin
  * terminitor plugin: add autocompletion also for edit, delete and setup subcommands.
  * terminitor plugin: add autocompletion for start subcommand.
  * Add basic autocompletion for terminitor (https://github.com/achiu/terminitor).
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * Textmate plugin update to take Gemfile and cucumber features in account
  * Added VCS prompt to Apple theme.
  * [plugins/grails] Remove warning message; it's always displayed
  * [plugins/grails] Use globbing instead of grep
  * [plugins/grails] Added grails plugin
  * fix completion for commands wrapped with bundler
  * New function `efile`
  * Merge branch 'master' of github.com:Gonzih/oh-my-zsh
  * vundle call fixed for new vundle version
  * add foreman, nanoc, and rainbows to list of bundled commands
  * order aliases alphabetically
  * Merge pull request #490 from hwti/428f18cf428fd86bd6e99c4363e5f25d0e392506
  * Merge pull request #408 from thunfischbrot/patch-1
  * Merge pull request #575 from mr-szymanski/master
  * Revert "Enable red dots during completion by default".
  * Add an alias for ga --> git add, too
  * Add gss alias for git status -s
  * Fix auto upgrade failure from non-exported ZSH env var
  * Rename to _capistrano (completion only)
  * Gallois theme - made the git branch/status show for those of us without rvm
  * Added nifty purple Apple theme.
  * Remove -s switch from apt-copy
  * oops, restore broken theme preview
  * detect rvm or rbenv and show ruby version
  * Merge pull request #545 from ches/patch-1
  * Add guard to bundler plugin's wrapped commands
  * Merge pull request #543 from dmondark/heroku-completion
  * Added a gradle build tool plugin
  * Heroku completion plugin
  * Merge pull request #492 from hwti/red-dots-completion
  * Merge pull request #512 from ichesnokov/master
  * Merge pull request #515 from rahult/feature/powder-plugin
  * Extend root ops, switch apt-copy to plain zsh
  * Add options for su(do) and apt(itude|-get)
  * Add functions for new GH repos.
  * Add functions for new GH repos.
  * Fix su commands
  * Merge "deb" and "debian" plugins.
  * Add bundle open alias, which open gem using EDITOR var
  * added option of setting another path to custom plugins and files
  * fixed theme chooser + options + list available themes + show all themes
  * add theme with command-line tips support
  * Added auto complete plugin for powder gem https://github.com/Rodreegez/powder
  * Fix edit-command-line binding
  * Merge in recent stuff
  * 'echo' did not show colors without -e in upgrade.sh
  * Merge pull request #464 from bkonkle/patch-1
  * Merge pull request #507 from walle/add_autocomplete_for_gas
  * Replace forgotten rubies with authors
  * Add autocomplete for gas. Based on the rvm plugin.
  * Add fino.zsh-theme
  * Enable red dots during completion by default
  * Merge pull request #494 from EspadaV8/master
  * Merge pull request #496 from semmons99/master
  * Merge pull request #502 from sunaku/history
  * move history-substring-search* files into plugins/
  * add alias for `bundle package` to the bundler plugin
  * The original SVN pluging would mark a folder as dirty if there was an svn:external set and the output of 'svn status' returned the check for the external. E.g.
  * Replace a duplicated test to see if we're in an SVN folder with a call to the 'in_svn' function.
  * Display red dots during completion process (disabled by default)
  * global zsh config
  * mac os fix
  * Add key bindings for gnome-terminal on Fedora
  * Merge pull request #488 from dreur/upstream-archlinux-plugin
  * Merge pull request #259 from dereine/master
  * Merge pull request #251 from kalasjocke/master
  * Merge pull request #215 from sunaku/history
  * Merge pull request #208 from sorin-ionescu/plugin-extract
  * Merge pull request #206 from sorin-ionescu/plugin-osx
  * Merge pull request #167 from jarinudom/master
  * Merge pull request #112 from lukerandall/master
  * fixing issue with last commit merge. missed a conflict
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * adding git svn aliases
  * added git log with graph
  * added mac keybinding for backward-delete-char
  * Merge pull request #412 from transat/master
  * Merge pull request #461 from dpoggi/master
  * Merge pull request #487 from dreur/upstream-spectrum-utility
  * More generic.
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Don't export oh-my-zsh configuration paramaters to the environment
  * Merge pull request #107 from philips/philips-theme
  * Merge pull request #484 from msabramo/f9bf396e4ac68299f1370ed54350cc14ce954eea
  * Remove sudo when using yaourt + do not rely on abs when not in path - In archlinux plugin
  * Add utility method to spectrum
  * Merge pull request #483 from dreur/upstream-archlinux-plugin
  * Fix typo
  * fox's theme + theme chooser fixes
  * added theme chooser
  * Merge pull request #480 from PabloSerbo/master
  * Bringing inline with oh-my-zsh coding convensions
  * Merge pull request #479 from csexton/edit-command-line
  * C-x C-e to edit current command in EDITOR
  * Merge pull request #474 from PabloSerbo/master
  * Merge pull request #476 from theunraveler/master
  * Merge pull request #452 from franklouwers/master
  * Merge pull request #468 from blinks/master
  * Merge pull request #477 from totolici/patch-1
  * Merge pull request #404 from gwjo/ssh-agent
  * Merge pull request #415 from eproxus/master
  * Merge pull request #475 from dreur/upstream-archlinux-plugin
  * Fixed typo for one of the subcommands (linset -> linsert)
  * Adding quotes to deal with paths that have spaces.
  * Added archlinux plugin
  * Completion for cake the coffee-script build tool
  * rsync: add rsync- prefixes and use aliases
  * Merge pull request #370 from lepht/taskwarrior-plugin
  * Merge pull request #451 from matthewmccullough/cloudappplugin
  * Merge pull request #467 from papercavalier/bundler
  * zsh-history-substring-search plugin at 15f63de
  * Added a new theme.
  * refactor _run-with-bundler
  * Minor corrections to deletion detection in git_prompt_status
  * Merge pull request #462 from papercavalier/bundler
  * clean up rails plugin, removing bundler-specific logic
  * alias bundle list
  * merge bundler and bundle-exec plugins
  * fix indentation
  * update bundled commands
  * Moved opening braces
  * forgot to rename one variable
  * changed names of functions and variables to fit naming conventions
  * use lowercase for variablenames
  * Added bundler-exec plugin
  * Added 'dpoggi' theme
  * knife autocompletion
  * added tip about vundle configutarion after git clone
  * vundle plugin refactored first it checks existens of vundle plugin, if plugin dont exist run git clone
  * Added cloudapp from @holman of @GitHub fame
  * Merge remote-tracking branch 'robbyrussell/master'
  * Updated the frisk theme to display Bazaar branch information as well (based on zedtux.zsh-theme http://j.mp/ikTZJj)
  * removing useless line
  * plugin for vundle (vim plugins managment system) that provide vundle, vundle-update and vundle-init aliases
  * Create gnzh theme
  * Merge pull request #429 from mhitza/master
  * Merge pull request #436 from smt/pull-request-1
  * Changed kanji to fuku (good luck)
  * Add ohmyzsh theme, my version of dogenpunk
  * rsync: add plugin
  * When the theme choice is left out, oh-my-zsh will not try to load it
  * use /home/ryan/d/.oh-my-zsh instead of ~/.oh-my-zsh for cache
  * Added mercurial plugin with aliases.
  * Add Django plugin. This is a slight modification of the Django zsh completions that I found at https://raw.github.com/technolize/zsh-completion-funcs/master/_manage.py
  * Fix MM lines being read correctly
  * Change plugin name from cap to capistrano
  * Rename guru theme to sunrise
  * Fix git R and M status when used together
  * Add note about Solarized color theme
  * Add email address
  * Merge remote-tracking branch 'robbyrussell/master'
  * Remove unused colors and use original prompt color
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Dollar sign instead of percent in unprivileged user prompt (as in real gentoo)
  * Included some essential aliases, inspired by http://lolcode.com/
  * New theme, Read contents for further customising.
  * Aliases
  * Merge pull request #400 from mkomitee/master
  * Add support for loading mulitple identities
  * Add support for agent forwarding
  * Fix bug from Pull request #395     #395 broke oh-my-zsh for users who disable check-for-updates
  * Merge pull request #395 from vguerci/upgrade-before-init
  * [upgrade] before init (no reload needed unless oh-my-zsh.sh has been modified)
  * Colorize Install & Upgrade Scripts
  * Merge pull request #371 from nebirhos/master
  * Merge pull request #378 from secondplanet/master
  * Merge pull request #391 from mattdoran/master
  * Fix typos in the svn plugin that would cause calls to 'svn' when not in an svn working copy.
  * Merge pull request #385 from sunaku/theme
  * add "sunaku" theme, see http://ompldr.org/vOHcwZg
  * Added gnu-utils plugin.
  * Handle tar.xz and tar.lzma better (credit: @gwjo).
  * Added extract plugin.
  * Added man-preview completion suggested by @webflo.
  * Vastly improved osx plugin.
  * Replaced npm 0.x completion with 1.0 completion.
  * Merge pull request #382 from miloshadzic/master
  * Merge pull request #380 from brianjriddle/master
  * Merge pull request #383 from alanpeabody/master
  * Adds my theme
  * Remove extra space when no status
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Revert "Added my zsh theme file, heavily based on sjl's" as it relies on a dotfile to be in ~/bin.
  * Merge pull request #375 from betawaffle/rollback-366
  * Merge pull request #381 from thePapacy/fix-git-zsh
  * Fix deleted in git.zsh
  * fix double -f and corrected format.
  * Improve unicode characters and git status
  * Add guru theme
  * added humza.zsh-theme
  * Remove Uneeded Lines
  * Rollback of Pull #366
  * Added nebirhos theme
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh into taskwarrior-plugin
  * Merge pull request #359 from theunraveler/master
  * Merge pull request #363 from Blattlaus/master
  * Merge pull request #366 from betawaffle/master
  * Merge pull request #368 from trapd00r/master
  * Merge pull request #365 from briankftse/master
  * add trapd00r theme
  * Fixed cap plugin
  * Merge branch 'plugins'
  * Thor
  * Cleanup
  * Add new 'minimal' theme
  * OS X Helpers
  * Node.js Helpers
  * Pow! Restart Helper
  * Brew Plugin
  * Gem List Helper
  * RVM Update Helpers
  * Helpful Listing Aliases
  * Ruby Switching Helpers
  * Added compatibility for the linux 'stat' command for the ant plugin
  * Added my own theme.
  * Adding ability to override plugins from the custom directory.
  * Merge pull request #345 from jacobat/master
  * Merge pull request #346 from jojahner/master
  * Merge pull request #196 from asymmetric/master
  * Merge pull request #226 from sunaku/fishy
  * Merge pull request #139 from clauswitt/master
  * Merge pull request #118 from fwalch/gpg-agent
  * Merge pull request #92 from re5et/master
  * Merge pull request #90 from steeef/steeef-theme
  * fishy theme: text indicators for $? and git status
  * Merge pull request #351 from GutenLinux/master
  * Merge pull request #347 from obcode/master
  * Merge pull request #355 from watsoncj/master^1
  * Adds oh-my-zsh plugin to load TaskWarrior completions
  * Adds the _task script included with TaskWarrior
  * Adds compl .swp caches to gitignore
  * Fix to random theme selection
  * Merge pull request #224 from Soliah/plugin-rvm
  * add custom completion support
  * Added obraun theme which is a slightly modified version of an already existing theme.
  * Added 'simple' theme.
  * Update, no more full path
  * TextMate automatically forks into the background
  * Add autojump plugin
  * Plugin to make WOL nice & easy
  * Add norm theme
  * Merge pull request #295 from alexrinass/apache2-macports-plugin
  * Merge pull request #290 from arthurkalm/delete-key-working
  * Merge pull request #322 from jonashuckestein/master
  * Merge pull request #324 from sorin-ionescu/plugin-compleat
  * Merge pull request #329 from juanghurtado/master
  * Merge pull request #330 from jtriley/jtriley-theme
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * remove git status from prompt
  * Adds support for $(current_branch) on git_parse_ahead()
  * Added Compleat - Completion for Human Beings plugin.
  * added my theme
  * Merge pull request #321 from nel/fix-window-title-regex.
  * Relax pattern matching on TERM. Closes #320.
  * Merge pull request #314 from mattsacks/master.
  * Merged pull request #315 from nebirhos/master.
  * Add fine-grained git prompt status to lukerandall.zsh-theme
  * fixed autoupdate
  * Add muse theme for 256 color terminals
  * Merged pull request #312 from juanghurtado/master.
  * Custom theme with Git support
  * Merged pull request #310 from Ikke/master.
  * Merged pull request #270 from sankara/d03a6176aacd583993c02c7e837d10751c431875.
  * Merged pull request #311 from papercavalier/rails3.
  * Rails 3 aliases now work with Rails 2 as well.
  * Added git-flow plugin
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Feature: Random themes now supported. Just set your theme to 'random' and it'll load a different theme each time oh-my-zsh is started. Closes #309
  * Merged pull request #308 from juanghurtado/master.
  * Adds new prompt methods on Git lib
  * Merged pull request #307 from jtriley/jtriley-theme.
  * Merged pull request #302 from JonathanTron/5bcfab37312511a7ffc3e8242ba8b8a622ecf061.
  * Merged pull request #303 from cit/master.
  * Merged pull request #299 from atmos/master.
  * Merged pull request #269 from oknowton/master.
  * Move sourcing of custom to below plugins
  * add my custom zsh prompt
  * add git-prompt plugin from olivierverdier/zsh-git-prompt
  * redis-cli.plugin.zsh removed, adding to the fpath isn't needed now
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * added alias for apt-cache search
  * Merged pull request #138 from murilasso/master.
  * Merged pull request #276 from saimn/yum.
  * Merged pull request #278 from totolici/redis-plugin.
  * Merged pull request #288 from dogenpunk/dogenpunk_theme.
  * Merged pull request #287 from arthurkalm/install-tweeks.
  * Merged pull request #294 from alexrinass/mysql-macports-plugin.
  * Merged pull request #297 from Soliah/master.
  * Merged pull request #298 from wolverian/master.
  * Merged pull request #300 from gallois/master.
  * added custom theme, based on eastwood
  * support non-standard rvm install prefixes
  * Add 'upgrade' to brew completions.
  * Made my them display the current rvm gemset and check for detached head state in git.
  * Added start/stop aliases for Apache 2 installation via macports.
  * Fixed folder naming for mysql-macports plugin and improved start/stop scripts.
  * Remove fpath/compinit code from github and npm plugins
  * Merge remote branch 'upstream/master'
  * Added bindings for Gnome terminal.
  * Make the delete key work correctly, instead of outputting a ~
  * Changed to use which.
  * Change URL to https since most corporate environments block git port.
  * Make the chsh more reliable.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Add new jonathan theme
  * Fix indentation
  * Fix alias `eeval'
  * - Fix pass of parameters - Add new function `ecd'.
  * redis-cli completion plugin
  * refactored pycrm command
  * More comments
  * I should not have merged this here.
  * new yum plugin with useful aliases
  * Removing master stuff
  * Merge branch 'master'; commit 'ca4dabb45e14d8cd38e07c4ffadf9473ceb2193b' into require_tool
  * Add new plugin emacs, to take benefit of daemon capabilities of emacs >=23
  * Fix version parsing. Now working with command $ zsh --version
  * New tool require_tool.sh
  * adding python plugin with some aliases
  * New plugin git-svn installing git project git-svn-clone-externals
  * Minor reformatting
  * github plugin: check for `ruby`.
  * Moved the plugin fpath loop and compinit so they happen before custom scripts are loaded.
  * Optimize plugin loading so that only one call to compinit is required
  * Moved compinit call back to oh-my-zsh.sh, after plugins are loaded
  * Add: new theme
  * Merge branch 'friskTheme' of https://github.com/Nycto/oh-my-zsh
  * Added the Frisk theme
  * Updating the README... now links to contributors page
  * kolo.zsh-theme
  * changes recommended by blueyed
  * Whoops, this was supposed to be in the last commit!
  * Moved this to the existing github plugin
  * blueyed's ZSH-fu is much stronger than mine.
  * no need for an extra fork
  * added hub plugin from defunkt
  * Revert "Enable alias completion, do not limit completion to just files"
  * Added npm plugin.
  * Using git-diff instead of git diff
  * Removing call to mate.
  * Fix `gdv`: make it a function, and use `view`.
  * Removed commented out code.
  * Moved the single compinit call from oh-my-zsh.sh to lib/completion.zsh
  * Replace redundant calls to compinit with a single call.
  * Refactor DISABLE_AUTO_TITLE to be more DRY
  * Command title behavior no longer depend on local zsh configuration
  * Escape characters used in escape sequence to avoid triggering bugs in Apple Terminal
  * Further git completion improovements
  * Completions are git subdommand-aware now
  * Zsh will now complete git aliases with git stuff
  * Merge branch 'disable_auto-title' of https://github.com/lorrin/oh-my-zsh into lorrin-disable_auto-title
  * Adding dogenpunk theme
  * Add a plugin to support kate the kde texteditor
  * fixed wget command in readme
  * Introduce DISABLE_AUTO_TITLE option
  * Make command-not-found no-op when support not available (e.g. not on Ubuntu)
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Lein completion
  * New theme 'intheloop' which demonstrates the git_remote_status function
  * Added new function git_remote_status to check if we are ahead, behind or diverged from the remote branch
  * Added terminal party theme.
  * Added the Frisk theme
  * Revert "Re-order title/tab setting to make window titles work on OSX terminal which" Was causing iTerm title to disappear entirely..
  * Merge branch 'ssh-agent-append-host-to-environment' of https://github.com/trcjr/oh-my-zsh into trcjr-ssh-agent-append-host-to-environment
  * Merge branch 'master' of https://github.com/AlexBio/oh-my-zsh into AlexBio-master
  * Merge branch 'osx-terminal-title' of https://github.com/curiousstranger/oh-my-zsh into curiousstranger-osx-terminal-title
  * Merge branch 'master' of https://github.com/dbbolton/oh-my-zsh into dbbolton-master
  * Merge branch 'feature/alias-completion' of https://github.com/shadowhand/oh-my-zsh into shadowhand-feature/alias-completion
  * Merge branch 'master' of https://github.com/tjkirch/oh-my-zsh into tjkirch-master
  * Add debian plugins file
  * No space before prompt char at beginning of line
  * Actually show return code on failure
  * Sweet lightning bolt on uncommitted git changes
  * Remove unnecessary whitespace
  * Make personal theme based on dst
  * add Perl plugins file
  * Re-order title/tab setting to make window titles work on OSX terminal which doesn't support tabs titles.
  * Add completion for port command
  * add 'deb' plugin with Debian's apt aliases
  * add completion plugin 'cpanm' for cpanminus
  * add 'lol' plugin (based on lolbash)
  * Enable alias completion, do not limit completion to just files
  * Merge ssh://spix-dev01/home/fredrik/.oh-my-zsh
  * figuring out home dir on unix systems as well
  * Merge branch 'master' of github.com:fred-o/oh-my-zsh
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * fix to avoid parse errors if $TERM is empty
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * Added a plugin for GNU Screen.
  * .gitignore
  * ssh-agent plugin now ends in "-$HOST" so an agent is started properly with nfs shared homes.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Refined RVM prompt in Crunch theme
  * Crunch theme (by Stephen Eley)
  * Add tab completion to bundler plugin.
  * Add tab completion for rvm.
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * no hg & git status (sloooow)
  * Merge branch 'master' of https://github.com/myronmarston/oh-my-zsh into myronmarston-master
  * Merge branch 'refactor-term' of https://github.com/nel/oh-my-zsh into nel-refactor-term
  * Merge branch 'master' of https://github.com/medwezys/oh-my-zsh into medwezys-master
  * Merge branch 'osx' of https://github.com/benlangfeld/oh-my-zsh into benlangfeld-osx
  * Merge branch 'master' of https://github.com/Soliah/oh-my-zsh into Soliah-master
  * Merge branch 'lib-git' of https://github.com/sorin-ionescu/oh-my-zsh into sorin-ionescu-lib-git
  * Merge branch 'master' of https://github.com/nanotech/oh-my-zsh into nanotech-master
  * Merge branch 'theme-sorin' of https://github.com/sorin-ionescu/oh-my-zsh into sorin-ionescu-theme-sorin
  * Merge branch 'master' of https://github.com/Nemo157/oh-my-zsh into Nemo157-master
  * Merge branch 'nicoulaj-theme' of https://github.com/nicoulaj/oh-my-zsh into nicoulaj-nicoulaj-theme
  * Add iTerm version of tab function (itab)
  * Make a cleaner version of the OS X tab function
  * Renamed theme.
  * Added my theme.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * mvn plugin
  * Add bundler plugin with aliases.
  * Should use https for all GitHub urls.
  * fixed typo in rails3 plugin and added one alias for migrating and redoing migration if it was successful
  * Merge branch 'master' of github.com:fred-o/oh-my-zsh
  * Add vagrant completion for individual VMs
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * Added modified while newly added and type change detection to git prompt modified status.
  * Fixed auto update.
  * Added sorin oh-my-zsh theme.
  * Added time since last commit to Soliah theme and changed some colours.
  * Refactor window and tab title in tty
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * add missing unrar flag
  * Merge branch 'master' of https://github.com/theunraveler/oh-my-zsh into theunraveler-master
  * Merge branch 'master' of https://github.com/SuprDewd/oh-my-zsh into SuprDewd-master
  * Merge branch 'postpone-theme-sourcing' of https://github.com/mkomitee/oh-my-zsh into mkomitee-postpone-theme-sourcing
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of https://github.com/Rixius/oh-my-zsh into Rixius-master
  * Merge branch 'dieter-theme' of https://github.com/Dieterbe/oh-my-zsh into Dieterbe-dieter-theme
  * Merge branch 'typo' of https://github.com/papercavalier/oh-my-zsh into papercavalier-typo
  * Merge branch 'master' of https://github.com/sunaku/oh-my-zsh
  * Merge branch 'master' of https://github.com/dannytatom/oh-my-zsh into dannytatom-master
  * Merge branch 'master' of https://github.com/flazz/oh-my-zsh into flazz-master
  * added newline
  * Personal Style
  * theme changes
  * changes to theme
  * add Rixius-Theme
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Added an option to remove file afterwards.
  * Added svn info in prompt with plugin.
  * Made git ignore everything  in custom, not only the .zsh files.
  * theme based on afowler with vi-mode support
  * Added lambda theme
  * Postponing sourcing of the theme until after local customizations
  * avoid forking subshell to test if user is root
  * Merge branch 'git' of https://github.com/papercavalier/oh-my-zsh into papercavalier-git
  * Merge branch 'master' of https://github.com/derekprior/oh-my-zsh into derekprior-master
  * Merge branch 'rails3' of https://github.com/papercavalier/oh-my-zsh into papercavalier-rails3
  * add "fishy" theme to emulate Fish shell's prompt
  * Support for more archive formats.
  * Added a function to extract various archives. Also an alias for the function.
  * Added function to mkdir and immediately change to it
  * Add superjarin theme that shows current Ruby version via RVM
  * Typo
  * Removed remote_console. It doesn't handle rvm, capistrano, and so on.
  * A rails3 plugin based on the rails plugin
  * Aliased git checkout as `gco`
  * Fixed typo
  * Updating theunraveler theme to include more detailed git info.
  * Merge branch 'kardan' of https://github.com/kardan/oh-my-zsh into kardan-kardan
  * Updated the PROMT.
  * Added new kardan theme.
  * gentoo-like theme w/ git_prompt_info
  * Don't export oh-my-zsh configuration paramaters to the environment
  * maven plugin
  * Merge branch 'master' of github.com:clauswitt/oh-my-zsh
  * Added ant plugin
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * better phrasing/documentation
  * reset exit code visual cues (not exit code itself) after showing once
  * add dieter theme v1
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Avoid duplicate path cropping
  * Add my prompt theme
  * Rename appearance.zsh so that it gets loaded after spectrum.zsh. Allows to use 256 colors in prompt themes.
  * changes
  * Merge branch 'fix-lighthouse-error-message' of https://github.com/mortice/oh-my-zsh into mortice-fix-lighthouse-error-message
  * Merge branch 'completions' of https://github.com/gwjo/oh-my-zsh into gwjo-completions
  * Merge branch 'joerc' of https://github.com/sargas/oh-my-zsh into sargas-joerc
  * Merge branch 'master' of https://github.com/Bira/oh-my-zsh into Bira-master
  * Merge branch 'master' of https://github.com/FedyashevNikita/oh-my-zsh into FedyashevNikita-master
  * Removed the echo statement - no need for that.
  * improved formatting; redundant attributes deleted
  * fixed formatting; dead code deleted
  * vagrant plugin autocompletion - initial version
  * themes/nanotech: Use the new built-in zsh color variables.
  * Added my own theme, based on macovsky-ruby and funky
  * Added phing plugin
  * Merge remote branch 'origin/master' into gpg-agent
  * Completion fixes
  * Fix lighthouse plugin error message
  * command-not-found package in ubuntu
  * merge from master
  * merge theme fixes from master
  * merge with master
  * merge with master
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Added gpg-agent plugin
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * Added own theme (based on robbyrussell)
  * themes: philips customize git/ls for developers
  * merging in changes from robby's repo
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * bugfix - moved gem info
  * Merge branch 'master' of http://github.com/svnlto/oh-my-zsh into svnlto-master
  * Merge branch 'master' of http://github.com/philtr/oh-my-zsh into philtr-master
  * Merge branch 'philips-theme' of http://github.com/philips/oh-my-zsh into philips-philips-theme
  * Merge branch 'title-fix' of http://github.com/philips/oh-my-zsh into philips-title-fix
  * changeing unicode characters that were causing issues
  * leaving out subcommands for now
  * adding comment and URL to github gem
  * added git log incl. stats for the past 5 commits
  * adding github plugin
  * themes: add philips theme
  * functions: fix title() to not match any $TERM
  * Fixing some minor redrew issue
  * Adding new gozilla theme
  * Improving git plugin so it can display much more data.
  * Add cloud.zsh-theme
  * merge master
  * use 256 colors, if available
  * should have newline at end of file.
  * adding my zsh-theme
  * added rkj theme - xion-chiamiov-plus + hg from thomasjbradley
  * fix untracked files checking
  * merge steeef.zsh-theme from master (removed submodule check)
  * merge steeef.zsh-theme from master
  * Removing capistrano aliases/functions from rails plugin (since cap is not rails-specific).
  * Add lukerandall.zsh-theme
  * adapt brew,gem,pip plugin to new structure
  * Merge remote branch 'origin/master' into restructure_plugins
  * Reorganizing plugins so that each plugin has it's own directory now so that any plugin-specific functions can be bundled within there.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of http://github.com/kennethreitz/oh-my-zsh into kennethreitz-master
  * Merge branch 'master' of http://github.com/vivekprahlad/oh-my-zsh into vivekprahlad-master
  * Merge branch 'dirpersist' of http://github.com/curiousstranger/oh-my-zsh into curiousstranger-dirpersist
  * Match xterm-color, the default OS X terminal
  * Tidying up the spacing to bring in line with coding standards
  * Merge branch 'ssh-agent' of http://github.com/gwjo/oh-my-zsh into gwjo-ssh-agent
  * Merge branch 'theunraveler_theme' of http://github.com/theunraveler/oh-my-zsh into theunraveler-theunraveler_theme
  * Merge branch 'named_dirs_completion' of http://github.com/kremso/oh-my-zsh into kremso-named_dirs_completion
  * Merge branch 'shifttab' of http://github.com/kremso/oh-my-zsh into kremso-shifttab
  * added steeef theme
  * Portable perl dirpersiststore because 'tail -r' doesn't work everywhere.
  * Add vi-mode plugin for vi-like editing
  * Do not complete named-directories
  * unset config_file is useless
  * Added theunraveler theme.
  * ssh-agent module
  * Removed unportable (and unnecessary) grep flags
  * Change zdirstore to variable
  * Added install instructions
  * Added installation function
  * Move dirpersist to plugin
  * Escape some metachars that trip up .zdirstore script
  * Escape &'s in path name.  Need to find general function for escaping all shell metacharacters.
  * Alias popd to remove deleted dirs from persistance
  * Initial pass at pesistant directory stack
  * Adding comments
  * Adding a plugin with aliases for macports
  * Merge branch 'pip_plugin'
  * Merge branch 'gem_plugin'
  * Merge branch 'brew_plugin_fix'
  * add pip completion and plugin
  * add gem completion function and plugin
  * Added the truly epic kennethreitz theme.
  * Removing '.' alias as it is overwriting a bash/zsh feature. Closes #63
  * fix problems with brew completion
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Switching to /usr/bin/env zsh instead of /bin/zsh in the installer
  * add fletcherm theme; a slightly modified copy of an old tonotdo theme
  * add simple mrtazz theme based on robbyrussell
  * update brew plugin from homebrew contributions
  * Merge branch 'master' of http://github.com/AlexBio/oh-my-zsh into AlexBio/master
  * Made the user_machine_size calculation generic. Pwned the function name.
  * Added my own theme based on pat's
  * add candy theme
  * Added my theme (nanotech).
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Adding a ggpnp which does a git pull followed by a git push.
  * updated the readme
  * added plugin to control macports mysql-server installation
  * Added my own theme.
  * Don't correct hpodder commands.
  * Added a minimum zsh version note.
  * Don't display dotfiles or reverse sort with ll alias.
  * Ignore commands that start with a space.
  * Don't auto-correct ebuild commands.
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Adding some candy to the upgrade script
  * Moving brew functions to it's own plugin
  * Moving current_branch() to git plugin
  * Moving some rails and osx-specific functions to their corresponding plugin files
  * Removing legacy completion code
  * Removing rake completion from lib/ as it was moved to rails plugin
  * Moving capistrano functions to rails plugin
  * Updating default .zshrc template file to include plugins declaration
  * Initial implementation of a new plugin system, so that people can managed which aliases/functions they want.
  * Eastwood theme with optional RVM support
  * adding my zsh theme -- only difference from robby's being that i'm using white instead of blue for legibility over brown
  * Added customized version of the wezm theme (mainly added username/host in the prompt).
  * Added my zsh theme file, heavily based on sjl's
  * aussiegeek theme (include showing rvm prompt)
  * Import rvm prompt
  * macowsky modified theme with ruby version on prompt
  * modified macovsky to support ruby version
  * Adds a new theme that only seems to work on Linux
  * Sprinkling some candy on this muffin.
  * added skaro theme
  * added my theme
  * New theme "daveverwer", based on "geoffgarside".
  * added my own theme
  * happy with my theme. caret turns red for root
  * my WIP theme
  * Added my own theme.
  * Add my preferred prompt
  * added the dstufft theme (based on prose by sjl)
  * Add my oh-my-zsh theme
  * share history with your zsh's on the same host
  * added my theme, based on xiong-chiamiov-plus but using vcs_info instead of just git
  * two aliases set to 'ss', clobbering rails script/server
  * my theme
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Merge remote branch 'NV/master'
  * Adds new duellj theme
  * Merge remote branch 'jreese/master'
  * updated my theme with the date and git branch (+ dirty or not)
  * Merge remote branch 'robbyrussell/master'
  * Unsetting config_file after loading config
  * Don't autoselect first completion entry (Fixes #14)
  * Removing rake autocompletion as this is apparently  baked into recent versions of zsh
  * Fixed color in last character of clean git info
  * 256 color theme with bright blue and orange
  * escape sequences so rprompt doesn't mess up
  * Added scpectrum script for easy 256 color theaming
  * makes git status prompt 4x faster
  * Ignore errors from compaudit when using `sudo -s`
  * Remove limit of two segments to PWD
  * Added screenshot link for jreese theme
  * Added theme "jreese" to oh-my-zsh
  * Make Shift+Tab move backwards in the menu
  * added my personal theme: the dallas them
  * git:(master) --> git:master Parenthesis removed
  * Arrow theme: http://elv1s.ru/i/zsh-arrow-theme.png
  * clean theme: username is now bold
  * improvements to the 'clean' theme
  * added "clean" theme
  * fork xiong-chiamiov theme for git support
  * Putting Git related aliases into git.zsh to have them in context.
  * adding quotes to tab()
  * Adding a function that will open up a ticket in Lighthouse based on the number and there being a URL in a hidden file.
  * Adding a nocorrect for the heroku command as it was getting triggered by heroku logs.
  * Based on a suggestion from robbyrussel, using env for greater compatibility.
  * Instead of using the user's standard shell, this script should be run using zsh, since that was the shell it was written for.  On my machine changes to my default shell only take effect when I log out and then long in again.  Plus, it's nice for people to be able to try oh-my-zsh out even if zsh isn't their default shell right?  :-)
  * Merge commit 'e429ff9e2bed41f88e3df3315b159fa79a7152fc'
  * Merge branch 'master' of git://github.com/macovsky/oh-my-zsh into macovsky/master
  * Updating check_for_upgrade script to fix issue when the LAST_EPOCH file/value got corrupted. Closes #32
  * no correction on gist
  * new theme
  * No correction on mkdir + removed duplicate nocorrect mv
  * Revert
  * Completion from history
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Adding current_branch function, which can be used like: git pull origin master
  * tonotdo theme: Back to the original
  * tonotdo theme still not like I wanted
  * tonotdo theme like I like it
  * Theme tonotdo upgrade
  * Gallifrey theme
  * gave credit to Nick for the rake autocompletion code.
  * Spiced up the tonotdo theme, some more
  * Spiced up the tonotdo theme
  * LS_COLORS fix for tonotdo theme
  * Improved the LS_COLORS in my tonotdo theme
  * Fixed all themes so tab-completion doesn't move the cursor to a weird position
  * Modifying changes for issue 25, to fix issue 27
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Revert "Added my prompt theme, with a tweak to the core oh-my-zsh to support it. My git_prompt_info function not only reports the branch and dirty status, but also whether or not the branch is ahead or behind of the remote, or both. It also switches the prompt colour from green to red if the previous command exited with a non-zero value (i.e. failed)."
  * Revert "Whoops, forgot to include this dummy precmd implementation."
  * Only using the contents of .ssh/known_hosts when the file exists for ssh/scp auto-completion. Closes issue #20
  * Removing gdb alias as it conflicts with an actual command for gdb. Closes #17
  * Revert "Fixed issue #19 'Rake not auto completing'.  The stat command syntax that was being used was not correct. Or at least on my machine.  See man page for the stat command"
  * Added initial jnrowe theme.
  * Fixed issue #25.
  * Fixed darkblood theme as in issue #23.
  * Whoops, forgot to include this dummy precmd implementation.
  * Added my prompt theme, with a tweak to the core oh-my-zsh to support it. My git_prompt_info function not only reports the branch and dirty status, but also whether or not the branch is ahead or behind of the remote, or both. It also switches the prompt colour from green to red if the previous command exited with a non-zero value (i.e. failed).
  * parse error fix
  * Enabled colors in ls and made it possible to theme them
  * added LSCOLORS
  * Joined the appearance so the theme can apply LSCOLORS too
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Adding devlog alias for tailing development.log for Rails
  * Skip the git word in this theme
  * Small fix, probably the smallest possible
  * Added my theme
  * Added darkblod theme.
  * Fixing some conflict residue that I missed in a commit/merge:
  * Merge branch 'master' of git://github.com/kastner/oh-my-zsh into kastner/master
  * Merge branch 'master' of git://github.com/mrinterweb/oh-my-zsh into mrinterweb/master
  * Fixing merge conflicts 886d97f41e72b8662232a2c6b196fb60508e4f67
  * lsa now uses coloring
  * ll doesn't show hidden files, lsa does
  * Merging conflict. 788c9af05684f4b9e39e7f15de2c06c4c8291cbd
  * Merge branch 'master' of git://github.com/mdonoughe/oh-my-zsh into mdonoughe/master
  * adding homebrew completions - and a function dir
  * Fixed issue #19 'Rake not auto completing'.  The stat command syntax that was being used was not correct. Or at least on my machine.  See man page for the stat command
  * Removed useless else
  * Fixing merge
  * extended path variable, temporary
  * Renaming script/server --debug alias to ssd to avoid conflict. Closes #1
  * added gcp alias (git cherry-pick)
  * Added some comment
  * Merge branch 'master' of git://github.com/wezm/oh-my-zsh into wezm/master
  * Merge branch 'cypher/master'
  * Added more aliases for Rails & git
  * Added ack-grep searching
  * Added git diff for vim (gdv)
  * Replaced source with .
  * Add my own theme
  * should probably use the value of CASE_INSENSITIVE
  * allow case sensitivity to be toggled
  * Fix cypher's theme for older zsh versions
  * Merge branch 'master' of git://github.com/cypher/oh-my-zsh into cypher/master
  * add xiong-chiamiov theme
  * Make "-" an alias for "cd -" (cd back to previous directory)
  * Add my (cypher's) zsh prompt
  * run update check *after* running custom configuration scripts. This means we are running it after $PATH has potentially been set up, which means it's more likely that commands like "git" will be found
  * Oh My Zsh gets a weekly auto-updater... the future is now!
  * Adding a script to check for upgrades
  * put everything in lib
  * merge upstream
  * Bumping up history to 10k commands
  * Updating README to mention custom/ directory
  * not ignoring example.zsh
  * Updating .gitignore to ignore everything but the example.zsh file in custom/
  * Moving some example files into custom/
  * Moving all zsh config options into a lib/ subdirectory to make way for some upcoming changes to directory structure and configuration options
  * Using compctl instead of compdef to resolve Issue #1
  * Merge remote branch 'upstream/master'
  * add in refcard note
  * more fixes, more or less have this as i want
  * further refactorings
  * misc useful
  * tidy up history
  * Added a new theme
  * would rather store history in $HOME and double size
  * some todo notes, take @chris2's titlebar improvements and poke at completions
  * minimalist
  * add in xterms / title hacks
  * Merge remote branch 'upstream/master'
  * Git 1.6 support
  * Improved git prompt handling
  * make correction work; this is a nicer way of handling typos in commands
  * some helpers to make directory traversal go easier....
  * Adding a little documentation for the git themes
  * Added risto theme and made git.zsh themable
  * Updating the name of the rake and capistrano task cache file to append a ~ to the end of the filename so it's easier to ignore in rails git projects. [#1]
  * Updating install process to copy your current environments PATH and adding it to the bottom of ~/.zshrc.
  * Merge branch 'master' of git://github.com/mwilliams/oh-my-zsh into mwilliams/master
  * added case-insensitive auto completion
  * Adding more useful aliases for Git.
  * Moving bindings into their own file. Updating aliases after moving out bindings
  * Trying out some zsh-fu. Using the for x (*.zsh) source  approach
  * Updating README to instruct people to copy the .zshrc template file versus symlinking it.
  * Updating installer to use the new template file. ~/.zshrc will now be outside of the repository
  * Updating the template file to use the oh-my-zsh.sh loader
  * Renaming template file one last time (for now)
  * Moving and renaming the zshrc file to a template file
  * Moving the loading of all .zsh files into a different file so that we can remove zshrc from the repository
  * Including a link to the Themes wiki page from the README
  * Added extra theme with full pathnames and hostname
  * Adding an upgrade_oh_my_zsh function to... well, upgrade Oh My Zsh
  * Removing left over theme reference to geoffs theme
  * Merging geoffgarside work
  * Adding an uninstaller tool
  * Adding zsh_stats function to show you which commands you run the most.
  * Move the spaces around again :P
  * Merge branch 'master' of git@github.com:geoffgarside/oh-my-zsh
  * Only calling git symbolic-ref HEAD when we are in a .git directory
  * Restructure spaces in git pieces
  * Switch double quotes for singles, fixes prompt issues
  * Add my own theme
  * Colour branch name and add dirty string
  * Change dirty git string to a yello X
  * Remove colour from ls command
  * Adding a file into log/ so that we have a log file to record history to
  * Remove PATH definition as we define this in .profile
  * Add geoffgarside theme
  * Merge branch master
  * Adding Evan's skinny, topless prompt.
  * Updating README with info about themes
  * Adding theme support so that people can share their zsh prompts with others. Users can set which theme to load in zshrc now.
  * Add tab, take and tm functions
  * Customise prompt value
  * Use my normal PATH instead of included
  * Strip colours from git.zsh
  * Swap out g alias to git
  * Add textmate aliases
  * Add in my normal s{s,d} aliases
  * Updating README to match new path for installation.
  * Changing order of loading zsh at end of install
  * Attempting to load zsh properly after auto-install
  * Checking if .zshrc is a file or a symlink.
  * Updating README with reference to auto-installer
  * Adding an installer tool
  * Adding a note about backing up your existing zshrc file
  * Updating README to show people how to change their default shell.
  * Removing some unused git-dirty parsing code.
  * Removed a bunch of aliases that I never use, which came from someone else I copied old config from
  * Removing a robby-only alias
  * Moving some more config into prompt.zsh to reduce amount of code in .zshrc
  * Info about contributing
  * Updating README regarding PATH info
  * Note about PATH
  * Making sure it's obvious to symlink to ~/.zshrc
  * Merge branch 'master' of git://github.com/eddorre/oh-my-zsh into eddorre/master
  * Adding some info to the Usage section of the README
  * Updating README
  * Loading all files in /Users/robbyrussell/oh-my-zsh that end in .zsh instead of specifying them manually
  * Removed Git Aliases comment since there are no Git aliases in this file
  * Updating README file
  * Changing path to oh-my-zsh in zshrc
  * Importing initial files after reorganizing stuff.
  * Adding initial gitignore file

n.n.n / 2014-04-14 
==================

  * Merge pull request #2685 from delynn/patch-2
  * Remove mailcatcher
  * Merge pull request #2329 from pstadler/brew-cask
  * Merge pull request #2663 from bobmaerten/docker-autocomplete-updates
  * Merge pull request #2651 from jehrhardt/fix-emacs
  * Merge pull request #2661 from mcornella/fix_title_tab_percent
  * Merge pull request #2659 from simonc/allowing-pow-path-with-spaces
  * Merge pull request #2658 from leifcr/rake-fast-issue
  * Merge pull request #2647 from bobwilliams/master
  * Merge pull request #2656 from philenotfound/master
  * Merge pull request #2652 from lukehorvat/patch-1
  * Merge pull request #2660 from KevinBongart/add-readme-to-rake-fast
  * Merge pull request #2662 from aeriksson/master
  * adding urldecode_json to compliment urlencode_json and updating readme.md; slight tweak to urlencode_json from previous commit
  * adding urlencode_json and associated README.md details
  * Matching autocomplete for Docker v0.9.1
  * Fix broken reverse-menu-complete keybinding.
  * adding the is_json tool and associated readme.md details
  * Escape % in $CMD variable
  * Add README file to rake-fast plugin
  * Allowing path with spaces in pow plugin
  * brew-cask plugin: use spaces instead of tabs
  * Merge branch 'master' of github.com:philenotfound/oh-my-zsh
  * New aliases for 'apt-get' and 'aptitude' as they were overwritten by later aliases
  * adding support for node
  * Adds command line aliases useful for dealing with JSON
  * Updates spectrum.zsh
  * $ZSH is the OMZ installation folder, not configuration
  * mention $ZSH_CUSTOM as suggested in #2295
  * suggest setting $LANG to fix #1286 and fix #1823
  * Fix export syntax of $GREP_OPTIONS
  * Rendering the 'vagrant box (remove|repackage)' completion code independant of Vagrant implementation details.
  * application completion
  * library completion
  * in hindsight, this is probably a bad idea
  * completion of targets
  * instance and cluster completion
  * node completion
  * help command, node completion
  * added _files values for certain options
  * completion options
  * added alias
  * added completions for all known arguments to all known commands
  * apparently, this file must exist for the plugin to load
  * added completion for all asadmin subcommands
  * avoid VCS folders
  * Move example plugin to the custom plugins dir.
  * Add completion for pip install -r - so that it autocompletes requirements filenames
  * Added an <esc> to the begining of everything. I ran something when I was in insert mode once and all it did was shove !args... into the buffer.  <esc> first.
  * Updated the README to include documentation on the postCallVim callout
  * Added an optional callout to the end of the interaction function. I put it in to allow me to put the window focus on MacVim / GVim depending on the different OS I happen to be on
  * Fixed: If you callvim on a non-existant file with a relative path, the CWD of the running gvim process is used, and that's not right.  We use the PWD explicitly instead, in this case
  * A plugin that makes it easier to interact with the (single) running instance of gvim
  * command to restart pow process
  * added powed command to list pow urls
  * fix gnzh theme to detect local rvm installations
  * Added link to wiki page for plugins to README.
  * Add gem build autocompletion
  * `setopt append_history` is not necessary.
  * Plugin: Rake-fast: Support both *nix and Darwin
  * New aliases for 'apt-get' and 'aptitude' as they were overwritten by later aliases
  * Fixed typos + made wording more consistent in zshrc.zsh-template
  * adding xargs -0 to node aliases
  * updated readme.md and using tab char for formatting with node
  * bug fix for node pp_json version
  * Add check for display list equals nil
  * updating README.md
  * adding README.md for jsontools
  * Merge pull request #2563 from bobwilliams/master
  * Merge pull request #2390 from LFDM/updating_spectrum
  * Merge pull request #2645 from ncanceill/template-zshrc
  * Merge remote-tracking branch 'upstream/master'
  * $ZSH is the OMZ installation folder, not configuration
  * mention $ZSH_CUSTOM as suggested in #2295
  * suggest setting $LANG to fix #1286 and fix #1823
  * Merge pull request #2643 from mcornella/patch-1
  * Merge remote-tracking branch 'upstream/master'
  * Fix export syntax of $GREP_OPTIONS
  * Merge pull request #1302 from cybozuty/master
  * Merge pull request #1262 from fred-o/glassfish-plugin
  * Merge pull request #1162 from nXqd/patch-1
  * Merge pull request #1117 from Peeja/move-example-plugin
  * Merge pull request #967 from wjlroe/pip-requirements
  * Merge pull request #1022 from derekwyatt/master
  * Merge pull request #1005 from cmar/powed
  * Merge pull request #995 from wting/fix_gnzh_ruby_detection
  * Merge pull request #990 from tommorris/master
  * Merge pull request #973 from dlee/gem_build
  * Merge pull request #750 from blueyed/history-drop-default-append-history
  * Merge pull request #672 from eMxyzptlk/zsh_reload
  * Merge pull request #662 from walle/add_autocomplete_for_gas
  * Merge pull request #646 from whittle/master
  * Merge pull request #2618 from bdubertret/fix-gwip-norm
  * Merge pull request #2634 from danchenkov/master
  * Merge pull request #2638 from miguelfrde/irb
  * Merge pull request #2605 from mhauserr/patch-1
  * Merge pull request #2615 from erbridge/fix_virtualenvwrapper_lazy
  * Merge pull request #2616 from Bounga/master
  * Merge pull request #2620 from reedriley/master
  * Merge pull request #2619 from korylprince/master
  * Sort bundled commands alphabetically
  * Merge pull request #2440 from m0nah/master
  * Merge pull request #2510 from pavoljuhas/master
  * Merge pull request #2531 from KevinBongart/rake-fast
  * Merge pull request #2637 from aforty/master
  * Merge pull request #2627 from loxley/add_knife_vault_cmd
  * Merge pull request #2631 from AntoineD/master
  * Merge pull request #2639 from jieryn/master
  * add common video formats FLV and WEBM
  * Add irb to the list of bundled commands
  * Merge pull request #1 from KevinBongart/brew-cask
  * Add new brew cask commands
  * Added a forward-delete fallback to bind Delete key
  * atom plugin
  * Aligned comments
  * Update key-bindings.zsh
  * added terminfo keys verification
  * Fix dirpersist plugin
  * Fixed errors if acpitool isn't installed on linux
  * Add chef-vault knife cmd support
  * Add scd plugin for smart change of directory.
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Don't show useless '[]' when chruby_prompt_info is empty
  * Fix gwip alias in git plugin when no files to rm
  * Merge remote-tracking branch 'upstream/master'
  * Don't set RBENV_ROOT to "$HOME/.rbenv" when using Homebrew rbenv
  * Merge pull request #2576 from jeffwilliams/master
  * Merge pull request #2597 from githubhjs/master
  * Don't lazy load the virtualenvwrapper.
  * Merge pull request #2539 from chriswiggins/master
  * Merge pull request #2549 from brandon-beacher/master
  * Merge pull request #2574 from thiagowfx/linux-battery
  * Merge pull request #2603 from docwhat/ssh-agent-hostname
  * Merge pull request #2607 from avonderluft/dev
  * Merge pull request #2613 from Fisiu/ignore-ssh-users
  * Remove copyright information, as per #2588
  * Ignore more users in ssh completion.
  * Merge pull request #2602 from blueyed/use-default-hosts-completion-2
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh into dev
  * add option to show dirty status of current dir
  * Merge remote-tracking branch 'upstream/master'
  * Added v as a keybinding to edit-command-line
  * Merge pull request #2380 from rkh/chruby-gallois
  * Merge pull request #2435 from tompelka/master
  * Merge pull request #2466 from jarus/steeef-virtualenv-fix
  * Merge pull request #2588 from kerimdzhanov/remote-themes-copyright-info
  * Merge pull request #2584 from joukojo/master
  * Merge pull request #2590 from zhouhua015/master
  * Merge pull request #2593 from bobmaerten/typo-docker-plugin
  * Merge pull request #2591 from kevinxucs/remove-extra-aliases
  * ssh-agent: prevent environment file from flapping
  * Fixing a few quirks in the latest installer updates (quoting /Users/robbyrussell/.oh-my-zsh and such). Also mentioining our twitter account after install
  * Use zsh's default for ':completion:*:hosts'
  * Merge pull request #2149 from cristim/master
  * Merge pull request #1355 from F30/key-bindings
  * Merge pull request #2072 from jorge-d/master
  * Merge pull request #2595 from ksamdev/git.io
  * Merge pull request #2421 from LFDM/rails_plugin_fix
  * Merge pull request #2518 from erawk/master
  * Merge pull request #2326 from zakkak/master
  * Merge pull request #1776 from ronshapiro/master
  * Merge pull request #1501 from gambhiro/master
  * Merge pull request #1085 from avit/install-path
  * Merge pull request #650 from tristan0x/emacs
  * Merge pull request #2600 from jontewks/patch-1
  * Update license year
  * Updating README to show the new install URL, which redirects to the raw files on github.
  * Merge pull request #2596 from ryanwmarsh/fixing_bureau_scrollback
  * List pkgs by size
  * Fixes #2467 tab completion scrolls back in terminal when using bureau theme
  * Add github url shortener
  * Fix typo in autocomplete arguments
  * Removed unsolicited aliases.
  * Fix hgsl alias.
  * Merge pull request #2341 from mcornella/title_backticks
  * Document alternate install paths via ZSH variable
  * Abort installer on errors
  * Write install path into .zshrc
  * Reference default install path from ZSH variable
  * Remove all copyright information in themes. Closes #2587
  * Merge pull request #2331 from posva/catimg
  * Merge pull request #2479 from mrbfrank/theme-agnoster
  * Merge pull request #1402 from sergeylukin/master
  * Merge pull request #2565 from theallegedjosh/master
  * Merge pull request #2579 from mfaerevaag/master
  * Merge pull request #2535 from IgorTimoshenko/feature/yii-plugin
  * Merge pull request #2556 from chrisjones-brack3t/fix/git-prompt-1-9
  * Merge pull request #2572 from kevinxucs/sublime-linux-fix
  * Merge pull request #2059 from felipec/fc/gitfast
  * Merge pull request #2529 from emanuelez/patch-1
  * Merge pull request #2525 from lukesteensen/update-go-plugin
  * Merge pull request #2481 from felds/master
  * Merge pull request #2366 from chuancong/patch-1
  * Merge pull request #2322 from dpsk/patch-2
  * Merge pull request #2166 from cap10morgan/no-clobber-rbenv-root
  * Merge pull request #2564 from miry/patch-3
  * Merge pull request #2287 from rumpelsepp/master
  * Merge pull request #2400 from bric3/svn_fast_plugin
  * Merge conflicts with af-magic theme
  * Cleaning up conflict with merge of #2330
  * added mvnjetty alias
  * added aliases for tomcat:run tomcat7:run
  * added mvn-update
  * Updated wd plugin to v0.3.0
  * Added dirhistory plugin.
  * Integrate changes from #1841.
  * added the linux implementation to the battery plugin
  * Fixed sublime plugin behaviors.
  * :panda_face: Added simulator alias for Xcode plugin
  * adding support for node
  * gem push alias and gem yank alias
  * add gem push alias
  * add gem build alias
  * Adds command line aliases useful for dealing with JSON
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * ..a fundamental piece of matter.
  * Merge pull request #2548 from puffnfresh/gitignore-plugin-url
  * Merge pull request #2544 from fduch2k/patch-1
  * Verification of convert inside the function
  * grab last item in list which is the branch instead of relying on position.
  * Much needed PEP8 love. Use spaces, not tabs.
  * Avoid 'title:parse error' with single quotes in $CMD Fixes #2182
  * Revert previous commit, escape %
  * Use single quotes also in $LINE definiton
  * Avoid evaluating special chars in $LINE on title command (fixes #2234)
  * Adieu l'ami.
  * Merge pull request #2541 from puffnfresh/cabal-sandboxes-info
  * Remove mailcatcher from the bundler plugin.
  * Fix remaining broken URL in gitignore function
  * Update gitignore.plugin.zsh
  * Merge pull request #2542 from puffnfresh/gitignore-plugin-url
  * Fix URL to gi (gitignore) function
  * Add cabal_sandbox_info function
  * Update battery plugin to show calculating - OSX
  * Added Yii basic command completion
  * Add rake-fast plugin for fast rake autocompletion
  * Improve oneline logs
  * update golang plugin to match official version
  * remove duplicate 'go' plugin, symlink to 'golang'
  * Updated _brew zsh autocompletion to latest Homebrew upstream
  * Merge pull request #2515 from nupfel/plugins/iwhois
  * Merge pull request #2516 from lukesteensen/patch-1
  * Add 'services' command to homebrew completion
  * provides iwhois command to use CNAMES under whois.geek.nz to find most accurate whois server
  * Add scd plugin for smart change of directory.
  * Merge pull request #2465 from klange/master
  * Merge pull request #2342 from blackjid/master
  * Merge pull request #2402 from bric3/battery_level_gauge
  * highlight the username when root
  * theme agnoster: remove trailing space
  * corrected branch character
  * Merge pull request #2368 from lumbric/master
  * updated url to latest powerline-patched fonts
  * Improve virtualenv prompt in steeef theme
  * Update nyan.plugin.zsh
  * change nyancat telnet server
  * Adds a method that print a battery gauge
  * Add Laravel4 plugin
  * Adding commit hash to branch name in my favorit rjk-repos theme.
  * Fixes _rails_command
  * Renames main plugin function to `svn_prompt_info`
  * Renamed the methods of this script
  * Added further cleanup and svn status information
  * No need to eval in rvm_prompt_info!
  * Heavy refactor of svn-fast-info
  * Merge pull request #2389 from driver2000/patch-1
  * Merge pull request #2398 from phstc/fixes-tmuxinator-plugin-find
  * Inline `parse_svn` to avoid leaky state
  * Report the SVN need upgrade
  * Fixes RPROMPT in af-magic.zsh-theme
  * Renames the file to prompt_info_functions.zsh
  * Adds documentation.
  * Adds all other dummy implementations.
  * new faster SVN plugin
  * Fixes tmuxinator plugin find on OSX
  * add brew-cask plugin
  * Merge pull request #2396 from soluwalana/master
  * escape dashes
  * Update git.plugin.zsh
  * Updates spectrum.zsh
  * Fix bad right prompt placing.
  * Refactors ruby_prompts.zsh
  * Joins ruby prompt files and adds ruby_prompt_info.
  * Adds chruby_prompt_info dummy function.
  * Returns false when rbenv is not found.
  * Returns false when rvm is not found.
  * Fixes rvm_prompt_info() in lib/rvm.zsh
  * add chruby info to gallois theme
  * fix name schema for sudo plugin
  * Add support to command "show"
  * Revert "Cancel update if the current user doesn't have write permissions for the oh-my-zsh directory."
  * Merge pull request #2358 from n-st/master
  * Cancel update if the current user doesn't have write permissions for the oh-my-zsh directory.
  * Prevents oh-my-zsh loading the .zshenv twice
  * Add rdmtc alias for rails plugin.
  * typo fix
  * catimg: fix exit without using source supresses errors from convert whilen converting, as they are usually just warnings
  * Fixed a dirs bug for catimg
  * Fix for virtualenv support - fixes #2328, fixes #2297, resolves #2319
  * catimg plugin allow to print an image to the stdout using convert
  * Improve comments
  * Improve comments
  * Merge pull request #2316 from BBonifield/master
  * Making auto-correction off by default
  * Merge pull request #2303 from petervanderdoes/git-flow-avh
  * Merge pull request #2296 from pstadler/master
  * Update git-flow-avh 1.7.0
  * source ~/.profile only if it exists
  * Merge pull request #2208 from onemouth/master
  * Merge pull request #2173 from jeffrey4l/venv
  * Merge pull request #2159 from pungoyal/master
  * Merge pull request #2176 from dejanlukan/spectrum
  * Merge pull request #2194 from kevinxucs/gitignore-fix
  * Merge pull request #2195 from KevinBongart/command_blacklist_for_bundler_plugin
  * Merge pull request #2215 from posva/rand-quote
  * Merge pull request #2255 from shadyproject/plugin/xcode-support
  * Merge pull request #2258 from amilaperera/master
  * Merge pull request #2262 from mfaerevaag/master
  * Merge pull request #1520 from prooftechnique/master
  * Merge pull request #1574 from adben/master
  * Merge pull request #1683 from mnme/master
  * Merge pull request #1087 from avit/install-template
  * Merge pull request #1136 from koraa/pull_req_fastfile
  * Merge pull request #1135 from koraa/pull_req_sinchar
  * Merge pull request #1134 from koraa/pull_req_helpers
  * Merge pull request #1201 from koraa/pull_req_debian
  * Merge pull request #2088 from Stibbons/gsemet_push_pep_pylint_completion
  * Merge pull request #2086 from Stibbons/gsemet_push_repo
  * Merge pull request #1883 from Stibbons/gsemet_push_source_profile_for_upgrade
  * Merge pull request #1866 from Stibbons/gsemet_push_common_aliases
  * Merge pull request #2003 from dongweiming/update-gem
  * Merge pull request #1950 from dongweiming/add-systemadmin-plugin
  * Merge pull request #1947 from dongweiming/add-sudo
  * Merge pull request #1931 from dongweiming/update-urltools
  * Merge pull request #1942 from dongweiming/update-powify
  * Merge pull request #1940 from dongweiming/update-supervisor
  * Merge pull request #1928 from dongweiming/add-hist-stamp
  * Merge pull request #1927 from dongweiming/modify
  * Merge pull request #1956 from emesix/patch-1
  * Merge pull request #2022 from Zhann/master
  * Merge pull request #2034 from kasperisager/master
  * Merge pull request #2097 from natecox/master
  * Merge pull request #2131 from stevschmid/patch-1
  * Merge pull request #1030 from solnic/master
  * Merge pull request #950 from sonicradish/master
  * Merge pull request #948 from excepttheweasel/master
  * Merge pull request #946 from rach/master
  * Merge pull request #781 from pilif/two-lined-pygmalion
  * Merge pull request #684 from masnick/master
  * Merge pull request #639 from MarcoPeraza/git_unpushed
  * Merge pull request #513 from randy909/fix-edit-cmdline
  * Merge pull request #306 from jtriley/git-prompt
  * Merge pull request #2198 from Larandar/master
  * Merge pull request #2202 from kevinxucs/themes-random
  * Merge pull request #2212 from bsiegel/bundler_bi_function
  * Merge pull request #2222 from jamesoff/fix-battery-plugin
  * Merge pull request #2229 from prubianes/master
  * Merge pull request #2236 from Isquariel/nvm
  * Merge pull request #2270 from michaelorr/slow-git-fix
  * Merge pull request #2272 from TuiKiken/master
  * Merge pull request #2292 from Atem18/master
  * Change `bi` alias to a function
  * Merge remote-tracking branch 'upstream/master'
  * Fixed lines 32, 33, 34 where one 'p' was missing in 'zypper' command.
  * Merge pull request #2290 from jtinfors/master
  * Merge pull request #2242 from sztupy/fix-mvn-color-locale
  * Merge pull request #2252 from henrique2010/master
  * Merge pull request #2254 from Atem18/master
  * Merge pull request #2286 from ych/master
  * Merge pull request #2260 from Stibbons/gsemet_push_sublime3_support2
  * Merge pull request #2285 from dhruvasagar/master
  * Merge pull request #2240 from Kriechi/master
  * Adds the hgsl alias for one-line shortlog convenience
  * Added migration notification for rails plugin
  * Merge pull request #2249 from pabrahamsson/obsd_colorls
  * Merge pull request #2275 from wjv/wjv
  * Added/modified some useful aliases.
  * Add FreeBSD support for autojump plugin
  * Added Amuse zsh theme
  * wd.plugin: Added checks, readme and completion
  * wd.plugin: Fixed nested dirs
  * Merge pull request #2261 from webframp/feature/chruby-plugin
  * Merge pull request #2259 from eddiemonge/patch-1
  * Merge pull request #2266 from ssm/plugin/pyenv
  * Merge pull request #2271 from ashleyh/master
  * Merge pull request #2273 from thibaudgg/patch-1
  * Merge pull request #2276 from christianschmidt/master
  * Update _pass to follow symlinks for completion
  * Merge remote-tracking branch 'upstream/master'
  * Use precmd hook for updating OS X proxy icon
  * Update _heroku config arguments (Heroku Client v3)
  * Add update statistics
  * fix pip plugin
  * adding a check for git config option to disable git_prompt_info() on a per repo basis
  * unified and improved Rails plugin
  * Add pyenv plugin
  * Add simple plugin for chruby ruby version manager
  * Add support for sublime 3
  * standardize logic blocks
  * Merge pull request #2084 from mekanics/update-pod-plugin
  * Merge pull request #2253 from eddiemonge/patch-1
  * Merge pull request #2209 from quodlibetor/pip-caching-fixes
  * Merge pull request #2257 from mfaerevaag/master
  * Added wd plugin
  * Rebranded plugin according to Zypper's official alias
  * no tabs in a space-d file
  * basic command line xcode functionality
  * add aliases to readme
  * add new alias to zeus
  * Add support for colored ls output on OpenBSD
  * Merge pull request #2219 from Profpatsch/theme-agnoster
  * Merge pull request #2244 from marcoccchan/master
  * Merge pull request #2218 from wari/linuxonly-rename
  * Merge pull request #2239 from santagada/master
  * Merge pull request #2243 from sabarishcrri/bundle_plugin_nobundle_fix
  * Merge pull request #2245 from cadusk/p3
  * python3 clean updated.
  * getting the projects name correctly and making compdef to work with mux alias
  * Use environment specific open command when creating a new Jira issue.
  * bundle plugin throwing error when bundle is not in path while initializing
  * Fix issues with special characters when running mvn
  * agnoster theme not showing virtualenv status
  * Added the Bureau theme
  * Added nvm.zsh to detect current Node.js version
  * Modification to the frisk theme to work with the BZR lib
  * Modification to the frisk theme to work with the BZR lib
  * Prevent errors in prompts if no info available. Define empty functions instead of none at all if we can't figure out the platform.
  * Merge pull request #2220 from nishigori/fix-bad-ps-syntax
  * Fix bad ps syntax in ssh-agent plugin
  * Forgot one symbol for hg.
  * Merge pull request #1529 from aquaplanet/fix-sshagent-openbsd
  * `linuxonly` doesn't work unless renamed properly
  * Merge pull request #2174 from oxnz/master
  * randquote plugin correcting an issue about encoding some people was having added a message when the user doesn't have curl added varibles for colors->easier to customize
  * Make the pip cache work with djangopypi2
  * pip: successfully cache all the packages
  * Update git.plugin.zsh
  * updated to the latest version of cocoapods 0.27.1
  * themes plugin now picks a random theme if no argument is provided.
  * Add "options" as a valide 1st argument
  * Add configuration placeholders to installer template
  * Re-add whitespace
  * Add command blacklist support to bundler plugin
  * Minor gitignore fix.
  * Merge pull request #1688 from mbauhardt/z
  * Merge pull request #2138 from Profpatsch/theme-agnoster
  * Merge pull request #2165 from kevinxucs/custom-gitignore-fix
  * Merge pull request #1963 from shajra/pr/gpg-fix
  * Merge pull request #2078 from tbuehl/master
  * Merge pull request #2192 from kevintraver/tmux-aliases
  * Merge pull request #2184 from jmagnusson/agnoster_respect_venv_disable_prompt
  * Merge pull request #2107 from maxd/master
  * Add tmux aliases
  * Fix: Agnoster theme added venv name even if disabled See http://www.virtualenv.org/en/latest/index.html\?highlight\=virtual_env_disable_prompt\#activate-script for info regarding this.
  * Added the spectrum_bls function, which prints all 256 colors set as the background.
  * add itunes function to control itnues from the terminal
  * Add support .venv folder as virtual env
  * don't clobber existing RBENV_ROOT & follow Homebrew's default behavior
  * Moved misplaced plugins.
  * gitignore fix for custom folder.
  * removing a github redirect during install
  * Added a completion plugin for the new aws-cli tool
  * Merge pull request #2132 from jkaving/forklift2
  * Merge pull request #2139 from deiga/patch-1
  * Merge pull request #2145 from futjikato/master
  * Updated completion to work with comma seperated list
  * Added gitignore plugin ( for gitignore.io )
  * Added '.jar'
  * Added '.war' extension to unzip
  * More expressive symbols for git and mercurial.
  * Add support for ForkLift 2 to the ForkLift plugin
  * Fix work_in_progress in empty git repos
  * Check bundler version to avoid error with unsupported command line arguments
  * Revert "Replace no unicode glyph on hexa string"
  * Merge pull request #2065 from prudprud/master
  * Merge pull request #1763 from jonilicious/master
  * Merge pull request #1967 from tchaudhri/gdc_git_alias
  * Merge pull request #2079 from paulmelnikow/subl
  * Merge pull request #2077 from paulmelnikow/nvm
  * Merge pull request #2060 from dchusovitin/bug-node-doc
  * Merge pull request #2066 from agronemann/patch-1
  * Merge pull request #2087 from Stibbons/gsemet_push_theme_chooser
  * Merge pull request #2098 from monstermunchkin/master
  * Merge pull request #2043 from quodlibetor/fix-pip
  * Merge pull request #2053 from fluxrad/mosh
  * Merge pull request #2093 from zdevex/fixCommentsInTemplate
  * Merge pull request #2099 from mchaisse/master
  * Merge pull request #1840 from yleo77/master
  * Merge remote-tracking branch 'robbyrussell/master'
  * Added WIP alert to the gallois' theme
  * Added WIP (work in progress) feature to git.plugin
  * jump plugin: fix autocompletion with single mark
  * Added virtualenv plugin data to af-magic theme.
  * Fixed comments in zshrc.zsh-template about disabling auto updates.
  * Merge pull request #1987 from zvirusz/patch-1
  * Merge pull request #2002 from stibinator/master
  * Merge pull request #1829 from docwhat/compinit
  * Merge pull request #839 from eproxus/sunrise-fixes
  * Merge pull request #2080 from Mehonoshin/bundler-parallel-installing
  * Merge pull request #1975 from fff/master
  * repo list search one level deeper
  * Completion for python, pep8, autopep8 and pylint
  * Display right prompt in theme chooser
  * New aliases for repo plugin
  * typo
  * updated the arguments list to the newest version (0.24.0) of cocoapods
  * Logo draft 1...
  * Merge pull request #2045 from jeroenjanssens/master
  * Fix aliasing pwd
  * Mark function asks for confirmation and uses basename of directory when no argument is given
  * Change marks function and remove 'function' keyword as suggested by pielgrzym in https://github.com/robbyrussell/oh-my-zsh/pull/2045#issuecomment-22820224
  * Add _completemarks function as suggested by pielgrzym in https://github.com/robbyrussell/oh-my-zsh/pull/2045#issuecomment-22826540
  * Merge pull request #2 from JustinAiken/feature/marks_autocomplete_avaiable
  * Support of parallel bundle install
  * Better filename matching
  * Filter out missing links with jump autocomplete
  * Sublime Text: Harmonize alias with the Sublime Text install instructions
  * NVM: Avoid providing completions when nvm is not installed
  * Add commonly used git stash aliases
  * Plugin for Node Version Manager
  * Add completion for package add and remove
  * Add autocompletion plugin for meteor command
  * Update bundler.plugin.zsh
  * Replace no unicode glyph on hexa string
  * Merge remote-tracking branch 'robbyrussell/master'
  * Fixed opening documentation on Linux (node)
  * gitfast: update to upstream v1.8.4
  * Add support for mosh (remote-shell) tab completion.
  * Add tab completion for jump plugin
  * Add jump plugin, which allows you to easily jump around the file system
  * Improve pip plugin options support
  * changed duck to ddg for alias
  * Merge pull request #2028 from AeonAxan/master
  * Merge pull request #1672 from miry/rails3_command_fix
  * Merge pull request #1790 from simlegate/master
  * Merge pull request #1961 from brenttheisen/issue_1952_pr
  * Merge pull request #1960 from mekanics/plugin-pod
  * Add Pure theme
  * Merge branch 'master' of https://github.com/AeonAxan/oh-my-zsh
  * fixed minor errors
  * Update README.md
  * add docker autocomplete plugin
  * Updates Zhann theme
  * added duckduckgo to web-search
  * added duckduckgo to web-search
  * Added completion for second argument for 'brew reinstall'
  * Merge pull request #1988 from jwarwick/mix
  * Merge pull request #1992 from jeromemacias/patch-1
  * Merge pull request #1994 from kennethgeerts/master
  * Merge pull request #1993 from zvirusz/patch-2
  * Updated gem plugin zsh completion (gem 2.0.3).
  * In capistrano completion show also tasks without description
  * Fix symfony command completion 'permission denied'
  * Added autocompletion support for Elixir mix command
  * Added 'reinstall' command to brew completion
  * Merge pull request #1980 from awidegreen/upstream
  * Merge pull request #1981 from trobrock/knife-ssh
  * No cat, and hide errors for missing cache file
  * Add knife_ssh command to make connecting to servers managed with chef easier
  * Fix ssh-agent plugin identities comment for using multiple identities.
  * set default value `--max-count=10`
  * Merge remote-tracking branch 'robbyrussell/master'
  * PLUGIN: gpg-agent: export SSH_* environment variables too
  * show file liste on 'pod push [REPO]' and tab, 'pod spec lint' and 'pod podfile-info'
  * fixed typo in tmux plugin
  * Added a 'git diff --cached' alias -> 'gdc'
  * fix gpg-agent "running already" check
  * Copy and paste of two functions from Ubuntu 13.04's version of /usr/share/zsh/functions/Completion/Unix/_git that were referenced in 46f0d8d. Fixes #1952.
  * correct filename in the comments
  * Merge pull request #1935 from mateitrusca/master
  * supplemented with options
  * Update jonathan.zsh-theme
  * Add a plugin for systemadmin ops and developer
  * show repos on pod push
  * pod-list
  * commands and subcommands
  * first few lines for the autocompletion of cocoapods
  * Add sudo plugin
  * Update powify for displayed parameter is not enough, and when there is no directory error
  * Add version option
  * fixed typo in tmux plugin
  * Add shell built method
  * Add option for show in the command execution time stamp in the history
  * Modify determine the oh-my-zsh installed in non-default path of the installed
  * Update gem completion
  * Merge pull request #1764 from johnjohndoe/feature/rails3-autocompletion
  * Merge pull request #1920 from dongweiming/update-coffee
  * Merge pull request #1916 from okuramasafumi/master
  * Merge pull request #1919 from dongweiming/breaking-change-bower
  * Merge pull request #1917 from brandonblack/rvm-plugin
  * Update coffee completion
  * The current version of bower is completely unavailable, plugin depth modification
  * rvm plugin: update to ruby version helpers and rvm-update
  * Change duplicated alias name
  * Add autocompletion for Rails3.
  * Merge pull request #1913 from chriskrycho/patch-2
  * Add more capable hg incoming and outgoing count handling
  * Merge pull request #1859 from ayushs/plugin-git-clean
  * Merge pull request #1864 from Stibbons/gsemet_push_git_plugin
  * Merge pull request #1865 from Stibbons/gsemet_push_repo_plugin
  * Merge pull request #1867 from telser/master
  * Merge pull request #1869 from lucasuyezu/env_logs
  * Merge pull request #1868 from mlacorte/master
  * Merge pull request #1880 from posva/rand-quote
  * Merge pull request #1876 from chriskrycho/patch-1
  * Merge pull request #1881 from iammichiel/patch-1
  * Merge pull request #1886 from tresni/patch-5
  * Merge pull request #1901 from geecu/autocomplete_required
  * Merge pull request #1708 from tessi/extend_mercurial_plugin
  * Merge pull request #1773 from essembeh/master
  * Merge pull request #1903 from andschwa/tmux_iterm2
  * Merge pull request #1904 from oohlaf/gpg-agent-fix
  * Merge pull request #1908 from UncleBill/patch-1
  * Merge pull request #1909 from gonghao/master
  * Merge pull request #1910 from dongweiming/add-celery-completion
  * Add celery completion
  * add virtualenv prompt support for agnoster theme
  * git-pull add --rebase option
  * Typo
  * Prevent starting multiple gpg-agents
  * Not loading home tmux confs when iTerm2 tmux integration is enabled
  * Adding support for iTerm2 tmux integration via option '-CC'
  * Merge pull request #1872 from gdetrez/new-powerline-range
  * Merge pull request #1873 from charlesjohnson/bundler-plugin
  * Merge pull request #1887 from tgkokk/git-slow-fix
  * Merge pull request #1889 from jerolimov/patch-1
  * remove unused function
  * autocomplete required packages as second argumet
  * Merge pull request #1756 from rkj/master
  * Merge pull request #1885 from eakret/termsupport-fix
  * Merge pull request #1894 from codewhale/master
  * Merge pull request #1893 from jeremydt/postgres
  * debian plugin: ignore alias in sudo/aptitude check
  * Add new plugin for homebrew installed version of postgres
  * Do not clear tab when calling it with an argument.
  * Merge pull request #1877 from spazm/virtualenvwrapper-cleanup
  * Merge pull request #1878 from spazm/virtualenv-cleanup
  * Correctly detect Rapid Board
  * Fixed slow behavior when using GitHub wrappers
  * Better super-grep
  * Escape both % and $ in the command line
  * New plugin 'common-aliases' for optional cutting edge zsh aliases
  * source ~/.profile for upgrading (to source the proxy configuration)
  * Adding a rebase option to git alias.
  * Messed up the comment somehow...
  * Random quotes from the internet
  * virtualenv cleanup: replaces subshell with prompt expansion.
  * virtualenvwrapper plugin cleanup
  * Add count for incoming and outgoing changesets.
  * Merge pull request #1870 from mfrobben/patch-1
  * Update bundler.plugin.zsh
  * Update bundler.plugin.zsh
  * Update the character used in powerline
  * Update README.textile
  * add some alias for git flow
  * Adding testlog and prodlog.
  * Fixed color on git prompt for superjarin theme
  * A cabal plugin based on the lein plugin
  * Improvement in the git plugin
  * New plugin for git-repo (https://code.google.com/p/git-repo/)
  * Added alias for git clean
  * Merge pull request #1849 from lemieux/master
  * fix the open command in linux using xdg-open
  * Merge pull request #1834 from croach/disable_untracked_files_dirty_fix
  * Merge pull request #1775 from marcusmueller/fixupgradetool
  * add gf alias for git flow
  * Merge pull request #1837 from xuhdev/web-search
  * Merge pull request #1839 from Kronuz/patch-1
  * Fixed recursion. Git not needed for it to work.
  * Add web-search plugin.
  * Adding a fix for the DISABLE_UNTRACKED_FILES_DIRTY option.
  * Create the zcompdump based on version and host
  * add search by filename and file content feature
  * Merge pull request #1803 from bebugz/patch-1
  * gentoo linux support
  * add git alias 'gcmsg' and stand for 'git commit -m'
  * add git alias 'gcmsg' and stand for 'git commit -m'
  * rename gcm to gcmsg and stand for 'git commit -m' #1790
  * rename gcm to gcmsg and stand for 'git commit -m'
  * rm alias gcm='git checkout master' and add alias gcm='git commit -m'
  * Merge pull request #1774 from kevinxucs/sublime-default-2
  * Merge pull request #1779 from lorn/fasd_update
  * Cache for fasd --init
  * plugged_in function
  * eliminated unnecessary cd and failing substitution
  * Change sublime text path select priority on mac.
  * Uncomment l alias
  * Update the wrong variable used in rb20 function. Fixes #1762
  * Fixed missing retcode function
  * extend mercurial plugin to be more like git/svn
  * Merge pull request #690 from essembeh/master
  * Merge pull request #1254 from systemfreund/master
  * Spin to bundler
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Resolving conflict with merge of #1058
  * Merge pull request #1633 from alec-c4/master
  * Merge pull request #917 from agate/patch-1
  * Merge pull request #1091 from jmazzi/patch-1
  * Merge pull request #1102 from drnic/git-config
  * Merge pull request #1225 from bobmaerten/patch-1
  * Merge pull request #711 from jasongill/textmate-plugin-improvement
  * Merge pull request #424 from hackedy/fix
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Resolving conflict when merging in #528
  * Merge pull request #922 from sbfaulkner/master
  * Merge pull request #1053 from cwoodcox/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Updating the README file
  * Merge pull request #1088 from avit/avit-theme
  * Merge pull request #818 from jmacdonald/master
  * Merge pull request #1569 from ZeroKnight/master
  * Resolving conflict with merge of #970
  * Merge pull request #1223 from bigjust/master
  * Merge pull request #1620 from hreese/gpg-agent_with_sensible_ssh-agent
  * Merge pull request #1490 from khrt/master
  * Merge pull request #1565 from serdardalgic/autoenv-plugin
  * Resolving conflict in #1266 merge
  * Resolving conflict when merging in 1570
  * Merge pull request #1575 from mguindin/agnoster-change
  * Merge pull request #1582 from To1ne/pushdminus
  * Merge pull request #1608 from swanandp/m_lion_terminal_same_tab_support
  * Merge pull request #1622 from hacfi/patch-1
  * Merge pull request #1634 from Anahkiasen/patch-1
  * Merge pull request #1641 from NeuralSandwich/master
  * Merge pull request #1702 from mbauhardt/copyfile
  * Merge pull request #1715 from dbohdan/master
  * Merge pull request #1724 from miry/rails_aliases
  * Merge pull request #1703 from marcparadise/mp/knife-chef-11-initial-support
  * Merge pull request #1704 from laggyluke/st3
  * Merge pull request #1718 from toctan/master
  * Merge pull request #1721 from z2v/hgplugin
  * Merge pull request #1707 from bkg/django-static
  * Merge pull request #1714 from f0y/07738ea86330b7b77127fc6f18474b3da2c6ecec
  * Merge pull request #1719 from MatthR3D/master
  * Merge pull request #1726 from rkj/master
  * Merge pull request #1728 from szines/patch-1
  * Merge pull request #1729 from statschner/master
  * Merge pull request #1739 from felipec/fc/gitfast
  * Merge pull request #1749 from johnjohndoe/feature/zeus-auto-completion
  * Merge pull request #1733 from jaseg/patch-1
  * Merge pull request #1734 from cborgia/master
  * Merge pull request #1737 from hron84/feature-bundler-add-cleanup
  * Merge pull request #1738 from ronshapiro/master
  * Merge pull request #1748 from tobiassjosten/patch-1
  * Merge pull request #1740 from felipec/fc/git
  * Merge pull request #1750 from JamesFerguson/master
  * Only trim remote names; be git-flow friendly
  * Update rails4.plugin.zsh
  * Add auto-completion for zeus.
  * Added 'jekyll' to list of bundled commands
  * Merge pull request #1745 from jtheoof/master
  * Merge pull request #1747 from dhemmerling/mvn_tomcat-redeploy
  * mvn plugin was missing "redeploy" completion for tomcat.
  * Added option to allow untracked files as non dirty
  * gitfast: fix prompt
  * gitfast: synchronize with upstream
  * git: fix parse_git_dirty()
  * Separate the battery_pct_remaining data into it's own function so that it can be obtained even if the battery is connected.
  * Adding undocumented clean command to completion
  * Edited Grammar in template file
  * The safe-paste plugin now works with tmux, too
  * Added git-flow-avh plugin.
  * Update rvm.plugin.zsh to the latest ruby versions
  * Return code instead of dollar sign
  * Added global aliases to use RAILS_ENV.
  * Edit some yaourt aliases and add some
  * command-not-found support for Arch Linux
  * Implemented UTF-8 support in fishy.zsh-theme.
  * Add colorize plugin
  * Merge pull request #1526 from filipechagas/master
  * Merge pull request #1531 from lcosmin/master
  * Merge pull request #1532 from ryanneufeld/torrent_tools
  * Merge pull request #1537 from everbird/master
  * Merge pull request #1540 from goofansu/add-rebar-plugin
  * Merge pull request #1651 from deepusudhakar/master
  * Merge pull request #1696 from henryyan/master
  * Merge pull request #1700 from Bercio/master
  * Merge pull request #1701 from mbauhardt/copydir
  * Merge pull request #1706 from keyvez/master
  * Merge pull request #1711 from bertabus/master
  * Added Vundle clean to remove bundles removed from vimrc
  * Support for Sublime Text 3
  * Use completions with django-admin.py
  * Add collectstatic to django command completions
  * Escape spaces in folder name so script won't fail
  * Add alias for 'hg bookmarks'
  *  initial support for chef 11 integrated knife-essentials
  * a plugin (function) which copies the content of a file into the clipboard
  * a plugin (function) which copies the current directory into the clipboard
  * Merge pull request #1699 from Bercio/patch-1
  * Merge pull request #1689 from afh/pull/emoji_clock
  * >! doesn't work with no clobber, echo is redundant. Fixed all.
  * "$PWD" = "PWD", >! doesn't work, echo is redundant. Fixed all.
  * Add emoji-clock plugin
  * Merge pull request #1208 from jaischeema/master
  * Merge pull request #1060 from danielbayerlein/new-theme-inspired-by-peepcode
  * Merge pull request #729 from doitian/plugin_tmuxinator
  * 005d967dc4e879f304607a706ccd18886e630dc1
  * Merge pull request #1632 from jmatth/tmux_plugin
  * Merge pull request #1652 from z2v/master
  * Merge pull request #1654 from bertag/parse-git-dirty-support-for-1.6
  * Merge pull request #1655 from nubs/phing-and-cache-files
  * Merge pull request #1656 from hacfi/patch-2
  * Merge pull request #1665 from bmcorser/patch-1
  * Merge pull request #1679 from KokaKiwi/master
  * Merge pull request #1680 from zbrox/master
  * Merge pull request #1681 from akre54/add-bower
  * Merge pull request #1685 from justinclayton/patch-1
  * Merge pull request #1686 from timsly/hub-autocomplete
  * Merge pull request #1690 from docwhat/git-untracked
  * Merge pull request #1662 from rylwin/patch-1
  * Merge pull request #1674 from simeonwillbanks/master
  * Merge pull request #1678 from lesmyrmidons/symfony2
  * Merge pull request #1682 from maplebed/ben.knife
  * Merge pull request #1691 from gianu/master
  * Merge pull request #1697 from dsx/sublime-plugin-fix
  * Merge pull request #1698 from ConradIrwin/safe-paste
  * +safe-paste plugin
  * Prevents echo of _sublime_darwin_paths contents
  * Added $PATH to PATH in install shell
  * Removed colors from parenthesis.
  * New theme: Gianu Theme
  * This fixes checking for git untracked items
  * ohmyzsh plugin of the z project: https://github.com/rupa/z
  * added hub autocomplete instructions
  * Update _vagrant
  * use hostname instead of hostname -s
  * adding docs about knife path config variables
  * allowing you to override knife paths
  * fix some references from npm --> bower.
  * add bower autocompletion
  * Powify autocomplete
  * Add 'kiwi' theme
  * Add colored man plugin.
  * modify alias sfc => sf
  * Simplification name aliases and adding new alias
  * Fixes #1485 zeus should not be bundled
  * Mercurial: add alias for pull with rebasing
  * Merge pull request #749 from blueyed/setopt-correct
  * Merge pull request #1657 from ysmood/master
  * Merge pull request #1658 from kavu/patch-1
  * Merge pull request #1659 from AshleyS/master
  * Merge pull request #1661 from hellerbarde/master
  * Merge pull request #1558 from sbooob/master
  * Merge pull request #1573 from flz/master
  * Merge pull request #1595 from nevir/sublime3-support
  * Merge pull request #1598 from zasdfgbnm/master
  * Merge pull request #1607 from gekken/master
  * Merge pull request #1610 from mcaserta/scala_and_sbt_plugins
  * Merge pull request #1611 from ripdog/patch-1
  * Merge pull request #1614 from miklos-martin/bower
  * Merge pull request #1616 from sxeraverx/master
  * Merge pull request #1524 from bonifaido/master
  * Merge pull request #1638 from RomainBelorgey/master
  * Merge pull request #1650 from ishtu/master
  * Merge pull request #1663 from flavius/master
  * Merge pull request #1664 from marcel-wolf/master
  * Merge pull request #1668 from sheerun/patch-1
  * Merge pull request #1669 from desimone/master
  * Merge pull request #1671 from lifinsky/master
  * Exporting path to fixed config as a global variable.
  * Prefixing tmux wrapper function with '_'.
  * IMPROVED: untracked file status has priority over modified (ie: if you have both modified and untracked files, your prompt will be red indicating the presence of untracked files)
  * Use new style of rails command.
  * Fix grails plugin
  * Added golang completion support from golang.org
  * Use --no-rehash option for faster startup
  * Alias for commit and commit all with amend
  * add ssh-agent option to set default lifetime of identities
  * allow setting a custom HISTFILE before oh-my-zsh is loaded
  * Fix whitespace
  * last-working-dir: Use >! to overwrite $cache_file
  * fix git_prompt_status() to not say the repository has untracked files all the time
  * Modified to use full parameter as newer versions of base64 uses lowercase D
  * Fix git dirty status in dallas.zsh-theme
  * opt: Optimize the color scheme. Add some basic comments.
  * Autocomplete composer default methods if composer.json is not available
  * Allow ":" and "-" characters in phing tasks.
  * Use [ -nt ] instead of stat -f%m to check cache files.
  * Merge remote-tracking branch 'upstream/master'
  * add: A new theme 'ys'.
  * Tweaked parse_git_dirty() in lib/git.zsh to support proper dirty/clean parsing against both git 1.6 and git 1.7+
  * Mercurial: add aliases for 'incoming' and 'outgoing' commands
  * Escape /Users/desudhak/.oh-my-zsh path (previously broke spaces in path)
  * add function vncviwer
  * Merge pull request #1645 from mbologna/master
  * added comment for auto-generated hostname color
  * added michelebologna theme
  * Updated battery plugin.  Displays charging time.
  * Update _capistrano
  * Add alias for "composer dump-autoload"
  * Added rails4 plugin
  * Checking to make sure tmux is actually installed before running plugin.
  * Adding options to choose tmux TERM for 256 and non-256 color terminals.
  * Adding compdef to maintain tmux completions.
  * Fixing typo in alias.
  * Adding option to prevent autostarting tmux more than once in the same session.
  * Checking if already in tmux before autostarting in tmux in tmux plugin.
  * Checking environment instead of local variable for fixing term in tmux plugin.
  * Fixing typos, logic, and gremlins in tmux plugin.
  * Adding helper tmux config files to tmux plugin.
  * Enabling autostart of tmux in tmux plugin.
  * Adding comments to tmux plugin.
  * Tmux plugin now just runs tmux if any extra args are given.
  * Now checking for 256 color terminal in tmux plugin.
  * Adding main function and alias to tmux plugin.
  * Starting tmux plugin with basic config variables.
  * Fix Symfony2 command completion 'permission denied'
  * Added --quiet to suppress message about gpg-agent already running.
  * Disable ssh-agent support if another ssh-agent is already running.
  * pipe git version check error to /dev/null (for when git doesn't exist)
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Update plugins/extract/extract.plugin.zsh
  * SBT and Scala plugins.
  * Support for opening tabs and windows in the same This fixed #1498 for me on Mountain Lion
  * Update plugins/rvm/rvm.plugin.zsh
  * Did a full circle and went back to # On branch master # Changes to be committed: #   (use "git reset HEAD <file>..." to unstage) # #	modified:   git.zsh #, ignoring untracked files, which seems to be the primary cause for slowness
  * Fixed dirty check to include files added to index
  * new plugin: start fbterm automatically in /dev/tty*
  * Merge remote-tracking branch 'upstream/master'
  * Merge pull request #1594 from jbhannah/rbenv-gems-fix
  * Merge pull request #1583 from To1ne/pj.plugin
  * Support for Sublime Text 3, with fallback
  * Fix rbenv gems helper
  * Merge remote-tracking branch 'upstream/master'
  * Merge pull request #1586 from HeroicEric/master
  * add alias for rspec to zeus plugin
  * added pj.plugin
  * use pushdminus
  * [agnoster] modifying theme to show dot for dirty files and plus for staged files in git repos
  * updated adben theme: added offline content, subversion support, refactored prompt
  * Add new profiles plugin.
  * Closer to original status command, using SUBMODULE SYNTAX
  * Better custom theme loading
  * Faster dirty git status check (using git diff)
  * Add autoenv plugin, which adopts using Kenneth Reitz's autoenv into oh-my-zsh.
  * ADDED: Mercurial prompt info support even if hg prompt extension is unavailable
  * ADDED: Mercurial repository info
  * Adding MIT-LICENSE Closes #655
  * Merge pull request #1534 from gberenfield/master
  * Merge pull request #941 from dcreager/configurable-blinks-theme
  * Merge pull request #1077 from Mezzle/add-option-to-show-git-status
  * Merge pull request #1054 from ptillemans/master
  * Merge pull request #1164 from fuksito/master
  * Merge pull request #837 from stacksmashing/master
  * Update to a better fab compeletion script.
  * Add rebar to plugin
  * Merge remote-tracking branch 'upstream/master'
  * Add new plugin to autocomplete fabric commands
  * Fixed coding style
  * moved bower plugin to a separate branch
  * cleaned up
  * Fix the fix for Issue #1479
  * fix for Issue 1479
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Adding torrent tools plugin.
  * Merge pull request #1510 from agnoster/agnoster-classic
  * Merge pull request #1517 from thisiskun/master
  * Fixes #1489
  * Fixed issue with NetBSD's ls
  * added support for subversion 1.7 for svn plugin
  * OpenBSD doesn't have -ef flags for ps. Both linux and OpenBSD have -x flags which works just as greate here
  * added crcandy theme
  * Fix gitfast problem for untracket files
  * Maven plugin completion fix for other (than Java) JVM languages
  * add symbol in darcs repos to match git and mercurial
  * add unbundled command
  * Revert "agnoster theme shows error code instead of an "x""
  * git lol
  * more catspeak
  * Added `verisions` option for `homebrew` completion
  * Merge pull request #1473 from bsteuber/fix-git-flow-feature-completion
  * Merge pull request #1475 from westonplatter/master
  * Merge pull request #1477 from madsgraphics/git_prompt_showstashstate
  * Add Stash toogle to display if there's some stash or not in `git_prompt_status`
  * fixes #1474 add zeus to bundle exec listx
  * use feature names instead of failing branch names in "git flow feature"
  * Merge pull request #1084 from avit/bwana-plugin
  * Merge pull request #1133 from mappleconfusers/605ad8725b06cc15f8523404f59060b6a71bb7a2
  * Merge pull request #1139 from mappleconfusers/pull_req_git
  * Merge pull request #1233 from mugenken/knife-check-cwd
  * Merge pull request #1467 from timothyandrew/patch-1
  * Merge pull request #1468 from larrylv/unset-config-file-variable
  * Unset `config_file` variable in oh-my-zsh.sh
  * Added a `migrate` alias.
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Merge pull request #1248 from grahamc/add-symfony
  * Merge pull request #1258 from caio/git-branch-status
  * Merge pull request #778 from rschmukler/plugin-osx
  * Merge pull request #794 from markdrago/cloud_parameter
  * Merge pull request #875 from ttddyy/prompt_git-remove
  * Merge pull request #880 from darrenclark/fix-mac-terminal-app-echo-issue
  * Merge pull request #1181 from paulmars/master
  * Merge pull request #1189 from petemounce/yum-quote
  * Merge pull request #1186 from r-darwish/history
  * Merge pull request #1247 from drnic/git-cmds
  * Merge pull request #1273 from ystein/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Resolving conflict in merge of #1313
  * Merge pull request #1387 from jimhester/vi-mode-patch
  * Merge pull request #1458 from ranman/master
  * Merge pull request #1454 from gAmUssA/patch-4
  * Merge pull request #1462 from aliasbind/master
  * Merge pull request #1460 from tresni/patch-4
  * Merge pull request #1459 from tresni/patch-3
  * Merge pull request #1463 from syphar/fix_last_working_dir
  * Fix prompt color: Change it back to green
  * plugin last-working-dir: create cache-directory if it doesn't exist
  * Print last exit status in mortalscumbag prompt
  * urltools for Everyone
  * Backwards Compatible Jira URLs #1378
  * use lazy load for virtualenvwrapper
  * hg_current_branch added to mercurial plugin
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Merge pull request #1457 from NeuralSandwich/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Fixing conflict in install scripts
  * Merge pull request #1328 from mfoo/master
  * Merge pull request #1301 from bencao/master
  * Merge pull request #1293 from cenkalti/master
  * Merge pull request #1295 from XL64/master
  * Merge pull request #1298 from nickhutchinson/fishy
  * Merge pull request #1382 from fushunpoon/master
  * Merge pull request #1191 from r-darwish/themes-plugin
  * Merge pull request #1235 from henryyan/master
  * Merge pull request #1241 from agrimaldi/git-extras
  * Merge pull request #1249 from korjavin/aptitude
  * Merge pull request #1255 from SuprDewd/master
  * Merge pull request #1256 from seegno/master
  * Merge pull request #1259 from bwl/sublime-fix
  * Merge pull request #1263 from tedv/headless-git
  * Merge pull request #1265 from aletessier/ssh-completion
  * Merge pull request #1274 from sc68cal/feature/git_decorate_log
  * Merge pull request #1277 from waveface/master
  * Merge pull request #1278 from bitboxer/forklift
  * Fixed Kernel Detection in battery plugin
  * Merge pull request #1284 from obmarg/feature/debianwhichfix
  * Merge pull request #1317 from thcipriani/junkfood_theme
  * Merge pull request #1319 from skatkov/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * resolving conflict in termsupport plugin
  * Merge pull request #1336 from aelesbao/plugin-systemd
  * Merge pull request #1341 from markusscherer/master
  * Merge pull request #1354 from F30/master
  * Merge pull request #1353 from a-b/master
  * Merge pull request #1371 from rdrey/master
  * Merge pull request #1376 from javageek/master
  * Merge pull request #1375 from dsx/better-pyclean
  * Merge pull request #1378 from hjhart/master
  * Merge pull request #1453 from simonoff/master
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * git find
  * Merge pull request #431 from meh/rsync-plugin
  * Merge pull request #409 from Bregor/patch-1
  * Merge pull request #214 from allancaffee/master
  * Merge pull request #1455 from NeuralSandwich/master
  * Merge pull request #1456 from sputnikus/master
  * Removing mcd as it conflicts with mtools
  * Renaming cap to capistrano
  * Functions for managing pacman-key
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Added Candy-Kingdom theme
  * Merge pull request #256 from lorrin/no-op_command-not-found
  * Merge pull request #253 from loopj/master
  * Added support for Mac to battery plugin
  * Update plugins/sublime/sublime.plugin.zsh
  * Merge pull request #516 from adben/master
  * Set default for rvm prompt prefix/suffix
  * Fix RVM loading and RVM ruby version info
  * Simonoff theme
  * Merge pull request #455 from aslamnd/master
  * Merge pull request #448 from n0nick/patch-1
  * Merge pull request #1451 from rmcastil/modify_readme_to_clarify_the_manual_way
  * Merge pull request #1452 from miry/github
  * Fix repo for github.
  * Make the NOTE an optional for improved instructions
  * Improve formatting of step 2 for clarity
  * Merge pull request #1393 from agate/patch-2
  * Merge pull request #1365 from pcasaretto/add-heroku-remote-switch
  * Merge pull request #1366 from op/last-working-dir
  * Merge pull request #1370 from ericmathison/syntax-fix
  * Merge pull request #1347 from paulredmond/plugin/jira
  * Merge pull request #1386 from sanbor/master
  * Merge pull request #1390 from pluton8/bugfix/autojump21
  * Merge pull request #1435 from Drarok/fix-svn
  * Merge pull request #1421 from cristim/master
  * Merge pull request #1399 from tresni/patch-1
  * Merge pull request #1400 from tresni/patch-2
  * Merge pull request #1416 from talmuth/master
  * Merge pull request #1410 from jimhester/per-directory-history
  * Merge pull request #1411 from niceview/rvm
  * Merge pull request #1413 from arnihermann/master
  * Merge pull request #1412 from jdavis/coffee_plugin
  * Merge pull request #1418 from Mehonoshin/patch-2
  * Merge pull request #1419 from ssrihari/master
  * Merge pull request #1439 from maxbane/master
  * Merge pull request #1442 from willman500/git-hub-flow-plugin
  * Merge pull request #1445 from knxroot/master
  * Modifying documentation in zshrc template for new config option
  * Merge pull request #1430 from danielsoneg/egd-update_frequency
  * Merge pull request #1437 from Partyschaum/master
  * Merge pull request #1446 from suzaku/patch-1
  * fix typo
  * Node.js version of urltools es more fast (53% aprox), you can try this with strace -o trace -c -Ttt
  * Add autocomplete for git "hubflow"
  * fixed autojump: autocompletion works with homebrew again
  * Merge branch 'master' of github.com:Partyschaum/oh-my-zsh
  * fixed autojump plugin: works with homebrew again now
  * Revert "Fix to restore bindings after switching to vi-mode"
  * fixed symbolic-ref git view of agnoster theme
  * removed 'x' from prompt_context() function name
  * Fix the backwards svn status, and add comments explaining which way grep does things.
  * Whitespace cleanup.
  * Add UPDATE_ZSH_DAYS setting
  * Merge pull request #1426 from caarlos0/master
  * fixes my wrong commit - fixes #1423
  * Merge pull request #1391 from logicmd/master
  * Merge pull request #1388 from fuadsaud/agnoster_theme_show_exit_status
  * Merge pull request #1395 from caarlos0/master
  * Merge pull request #1406 from chinghanho/master
  * Merge pull request #1404 from Bklyn/master
  * Merge pull request #1396 from webframp/fix/brew-autojump-zsh
  * Merge pull request #1415 from jmatth/git_root_pull
  * Merge pull request #1417 from felipec/fc-git-upstream
  * Added a small mod of the tjkirch theme
  * Added alias to rake db:test:prepare
  * Added gwc(git whatchanged alias)
  * Add gifast plugin
  * e alias
  * fixing various issues with build, add runinstall option
  * fixing some build issues...
  * Add support of screen-* $TERM in screen plugin
  * fixing issue with solr in jboss start
  * go
  * param -i para gerar installer
  * oops
  * totvs utils
  * Adding grt alias to the git plugin.
  * Use pull --rebase for 'gup' shortcut.
  * Added host to prompt
  * Added sf Symfony2 binary alias
  * Added a CoffeeScript plugin.
  * Use rvm completion from ~/.rvm/scripts/zsh/Completion
  * Replace reset-prompt with push-line and accept-line
  * Improved statistics functions, effect:
  * Untabify
  * Handle metachars in svn status output using grep -q
  * Fix /bin/sh compatibility issue in install.sh
  * Update plugins/svn/svn.plugin.zsh
  * Update themes/minimal.zsh-theme
  * made dpkg -i more util
  * update autojump plugin for latest brew installed autojump
  * mvn.colors.plugin.zsh was not read... mergin with mvn.plugin.zsh.
  * Added some maven love.
  * Update plugins/git-flow/git-flow.plugin.zsh
  * Update plugins/sublime/sublime.plugin.zsh
  * Fix sourcing brew's autojump of version 21.0.3+
  * agnoster theme shows error code instead of an "x"
  * Fixes for vi-mode terminal overwriting bugs
  * Added pass plugin in order to provide completion.
  * Expand for-loop so that it works under Snow Leopard Terminal.app.
  * Update plugins/jira/jira.plugin.zsh
  * Updated code from answer URL
  * Added ability to specify list of directories for pyclean to override default current directory
  * Fixed node-docs
  * Fix color syntax
  * Added last working directory plugin
  * Add the heroku --remote switch
  * Replace hardcoded key escape sequeneces with dynamic ones from terminfo.
  * add git-extras plugin
  * Merge remote-tracking branch 'upstream/master'
  * Make sure the terminal is always in application mode when zle is active.
  * Don't clobber standard Esc+. behavior
  * forgot to save before committing. doh
  * Added documentation to key bindings.
  * Set the '-R' option for less not in $PAGER, but as $LESS.
  * updated symbol
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Something to be said for symmetry
  * spacing makes me something
  * parens tweak
  * removed weird characters
  * moved spacing
  * Wrong URL :zap:
  * Merge pull request #1344 from danielcsgomes/master
  * Merge pull request #1306 from josh-/master
  * Merge pull request #1312 from koenpunt/fixes_cap_plugin
  * Merge pull request #1330 from trobrock/hide-rvm-prompt
  * Merge pull request #1333 from b4mboo/master
  * Merge pull request #1335 from paulredmond/plugin/jira
  * Merge pull request #1346 from ianchesal/urltools
  * make README reflect latest changes
  * URL Tools Plugin
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * added a comment to the composer installation alias
  * added Composer completition and aliases
  * added two aliases to Symfony2 Plugin
  * fix title setting bug in xterm and urxvt
  * fix test aliases
  * Missing comment line
  * Added systemd plugin with aliases for systemctl commands.
  * look for test/unit instead of test/units. #typo
  * Correct error message.
  * Merge pull request #1327 from agnoster/master
  * Clean up doc
  * Jira ticket shortcut to browse existing issues or create a new issue.
  * Merge remote-tracking branch 'upstream/master'
  * Add zeus plugin
  * Make rvm prompt function a bit cleaner
  * Fixing the rvm_prompt_info command, now it will not show empty parens if no rvm is currently being used
  * Add user-local installation autojump zsh plugin source
  * Add link to gist
  * Updated documentation for agnoster theme
  * Merge pull request #1318 from trobrock/add-puma-to-bundler
  * Merge pull request #1320 from jimhester/vi-mode-patch
  * Merge pull request #1321 from jimhester/per-directory-history
  * Merge pull request #1322 from jimhester/colemak
  * Merge pull request #1323 from lxmonk/autojump-port
  * Use HISTFILE evironment variable directly rather than copying it
  * added autojump plugin support for mac os x + port
  * Red prompt for remote hosts
  * Colemak plugin
  * Per directory history plugin
  * Fix to restore bindings after switching to vi-mode
  * Last spacing adjustment...I swear
  * Modified spacing one last time
  * Replace cp verbose with rsync
  * Bundle exec puma also http://puma.io
  * modified spacing on junkfood theme
  * Added fat arrow the theme
  * Refactored theme
  * Added space to prompt
  * Added junkfood theme
  * git plugin: Add `gpoat` alias
  * Add agnoster.zsh-theme
  * fixed incorrect if/else
  * updated cap plugin to use `cap -T` instead of `cap show_tasks` which didn't exist (sometimes?)
  * Merge remote-tracking branch 'upstream/master'
  * fixed nginx vhost template, made variables local, imroved parameter validation
  * Merge remote-tracking branch 'upstream/master'
  * added lesscss plugin
  * Add new 'nanoc' plugin
  * Nuke _cap_does_task_list_need_generating
  * Rendering the 'vagrant box (remove|repackage)' completion code independant of Vagrant implementation details.
  * fix rvm auto complete, pointing to $rvm_path
  * nginx and php-fpm plugins
  * Update fishy theme to collapse working directory in PROMPT.
  * Merge pull request #1228 from clutt0n/master
  * Merge pull request #1287 from johnhamelink/master
  * Merge pull request #1279 from 3den/master
  * Merge pull request #1297 from everbird/master
  * add new plugin to autocomplete supervisor commands
  * Add empty function rbenv_prompt_info() if doesn't exists
  * search virtualenvwrapper.sh in PATH
  * Added another path for virtualenvwrapper plugin
  * Add keep branch option.
  * Added laravel plugin which gives aliases to artisan and bob, and provides autocompletion for artisan.
  * Debian plugin now pipes which stderr to stdout
  * new 3den theme with RVM and GIT
  * Merge branch 'master' of github.com:ptillemans/oh-my-zsh
  * new forklift plugin
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Add shortcut for showing log of all branches
  * fix typo in cd-wrapper
  * application completion
  * library completion
  * in hindsight, this is probably a bad idea
  * Correct variable used for global ssh known host completion
  * Make git use sha when branch name is missing.
  * completion of targets
  * instance and cluster completion
  * Add branch status support to git_prompt_status
  * Adding logic for ~/Applications folder installs of Sublime Text 2
  * Add a configuration option to disable autocorrect
  * Added a "please" alias for sudo
  * Merge branch 'master', remote-tracking branch 'rr/master'
  * Added go completion script. Taken from /misc/zsh/go
  * alias at=aptitude broke /usr/bin/at scheduler. Just an idea: change it to ap
  * Merge
  * node completion
  * delete os specific disable-patterns
  * help command, node completion
  * Adding a symfony plugin, for symfony 1
  * improvement: define PROMPT_HOST once on startup
  * added 'gcl'for 'git config --list'; and gd for 'git diff'
  * Merge pull request #1229 from seban/run_rails_without_bundle_exec
  * auto-upadate feature will now reset the epoch so that if a user doesn't say yes, it won't ask them again for a while. fixes #1240
  * Fix changelog --list completion bug
  * Added credits
  * Added git-extras completion
  * Added avit theme
  * Bwana plugin for reading man pages in Safari
  * add maven zsh autocomplete plugin, copy from juvenxu's bash maven autocomplete plugin
  * check for knife.rb in cwd
  * merge from upstream master
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * modify themes/jnrowe.zsh-theme, add host directive "Ξ (mbsd) ~ →"
  * 'rails' command should not be run with bundle exec
  * added _files values for certain options
  * completion options
  * added alias
  * added completions for all known arguments to all known commands
  * vagrant uses 'ssh-config' command, not 'ssh_config'
  * Add very basic virtualenv plugin
  * Merge pull request #1200 from andyfleming/master
  * apparently, this file must exist for the plugin to load
  * added completion for all asadmin subcommands
  * Merge pull request #1206 from Eustachy/upstream
  * Merge pull request #1216 from joshvermaire/patch-1
  * utilize sublime's embedded command line binary
  * escape whitespace
  * Merge pull request #1122 from varunkvv/master
  * Merge pull request #1127 from a-b/master
  * Merge pull request #1193 from bameda/master
  * Merge pull request #1209 from lwe/rbfu-plugin
  * Merge pull request #1170 from dipth/master
  * provide plugin for rbfu the ruby version switcher
  * Fix the rvm gemset right prompt:wq
  * Add new theme : jaischeema
  * Remove bogus "-" from nomz="ps -aux" alias.
  * Remove debug info
  * Dynamicly generate completion functions to support changing apt_pref
  * Add myself to the authors list
  * Use a static apt-get where only apt-get works
  * Add completion instructions for apt/aptitude commands
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of github.com:essembeh/oh-my-zsh
  * Comment l alias
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Merge remote-tracking branch 'upstream/master'
  * Added another path
  * Merge pull request #1190 from vpacher/master
  * Merge pull request #1192 from rcakirerk/a39c9ffe5b7236b6e4dc78efa80b478cc411af7f
  * Fix finding git issue. http://stackoverflow.com/questions/592620/check-if-a-program-exists-from-a-bash-script
  * Added completion to the theme selection plugin
  * Added themes plugin
  * added jexec
  * added plugin for jruby
  * Fix mismatched quote in yum plugin
  * Merge pull request #1174 from insside/rbenv-homebrew-fix
  * Merge pull request #1126 from natsumesou/fix-ignore-symlink
  * Merge pull request #1182 from jugyo/patch-1
  * Merge pull request #1159 from kristi/master
  * Merge pull request #1173 from walkah/virtualenvwrapper-osx-fix
  * Merge pull request #1168 from r-darwish/yum-plugin-fix
  * Added history plugin
  * correct the ruby version label for rbenv
  * add git remote branch autocomplete
  * theme cleanup
  * added first version of my theme af-magic
  * sanitized code according to coding style
  * rbenv plugin now uses 'brew --prefix rbenv' command to find rbenv folder
  * remove readlink call and clean up
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Explicitly tell rbenv to use zsh
  * Fixed unmached " in yum plugin
  * More usable and shorter aliases
  * avoid VCS folders
  * Merge pull request #977 from scialex/better-d
  * Merge pull request #980 from vmalloc/dircycle_plugin
  * Merge pull request #984 from vmalloc/less_r_pager
  * Merge pull request #985 from pomaxa/master
  * Merge pull request #999 from ChaosData/master
  * Merge pull request #1016 from fuksito/master
  * Merge pull request #1032 from r-darwish/suse
  * Merge pull request #1055 from daniellockard/patch-1
  * Merge pull request #1065 from ntpeters/patch-1
  * add --directory flag
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Updating README to ask people to stop sending themes for now
  * Merge pull request #1148 from erichmenge/git-flow-plugin
  * Merge pull request #1019 from matschaffer/patch-1
  * Use grep to detect if untracked files exist instead of storing all the output of ls-files.
  * Merge pull request #239 from fred-o/master
  * Merge pull request #1146 from westonplatter/master
  * Merge pull request #1152 from mispy/virtualenvwrapper
  * Merge pull request #1155 from s3dev/s3dev
  * Merge pull request #1145 from tjl2/master
  * Merge pull request #1156 from thackoun/master
  * fix a very minor bug with colors of parenthesis in the terminalparty theme
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Change hardcoded ~/.oh-my-zsh to $ZSH.
  * Plugin which loads Python virtualenvwrapper and activates virtualenvs on cd into git repos
  * Merge branch 'master' of github.com:westonplatter/oh-my-zsh
  * checking if airport allows git protocol
  * Merge remote branch 'upstream/master'
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Added spin to bundled_commands (Bundler plugin)
  * Add a couple of options for git-flow.
  * rails3, added rgm = 'rails generate migration'
  * Removing ey command from bundled_commands. It is not usually bundled.
  * Merge pull request #1138 from amarraja/master
  * Merge pull request #1140 from mappleconfusers/pull_req_debian
  * Now with 50% less auto-updates.
  * Add command to directly install the output of acs
  * Make the $apt_pref variable evaluatet at alias expansion by using single-quotes instad of double quotes
  * Add aliases for git-remote: gr...
  * Prevent the heroku command from being automatically bundle-exec'ed The heroku command should not be executed via bundler, see: https://github.com/heroku/heroku/issues/173
  * Enhance handleing of spaces in filenames
  * Add the fastfile plugin
  * Make (s)xf not search in current dir
  * Make grep recoursive
  * Enhance file find
  * Add Man
  * Add file finders
  * Enhance writing routines
  * env_defaul=>env_default
  * Add sudo without xargs shortcuts
  * Add pager shortcuts
  * Add download shortcuts
  * Add a description
  * Add cat (+write, +append), enhance formatting
  * Add the singlechar plugin
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Add helper to easily define default values for variables and env variables.
  * Add helper to get the value of an alias only
  * Fixed a bug in checking the platform
  * fino-time theme
  * add fasd plugin
  * Load symlink custom files
  * Add Sublime Text 2 alias for Linux.
  * Added zp and zps aliases for the SUSE plugin
  * Added suse plugins
  * Merge pull request #1026 from dir01/patch-1
  * Merge pull request #1079 from dylnhdsn/feature/sublime_text_plugin
  * Merge pull request #1105 from Drarok/fix-svn
  * Merge pull request #1111 from jimeh/fix-ZSH_CUSTOM-variable
  * Move example plugin to the custom plugins dir.
  * Load themes from `$ZSH_CUSTOM` instead of `$ZSH/custom`
  * Suppress "zsh: no matches found" error when $ZSH_CUSTOM has no files
  * Don't drop everything after a trailing slash, as this breaks standard svn branches: ^/branches/featurename ^/releases/Release-vx.y ^/trunk
  * added 'gcl'for 'git config --list'; and gd for 'git diff'
  * Fix formatting
  * Add instructions on handling updates and prompts.
  * changed the alias to use to cli provided by sublime text
  * added aliases for sublime text
  * Add option to disable status notification
  * Merge remote branch 'upstream/master'
  * Added yum aliases for: makecache, grouplist, groupinstall, and groupremove.
  * Add Theme "itchy"
  * Adds glo; glp (arg)
  * Added an if-statement to see if git is installed
  * Added subcommands for leiningen 1.7.0
  * command to restart pow process
  * small changes to make it prettier
  * add the half-life theme based on steeef and lambda
  * Added an <esc> to the begining of everything. I ran something when I was in insert mode once and all it did was shove !args... into the buffer.  <esc> first.
  * Updated the README to include documentation on the postCallVim callout
  * Added an optional callout to the end of the interaction function. I put it in to allow me to put the window focus on MacVim / GVim depending on the different OS I happen to be on
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * [themes/josh] Use $(current_branch) in prompt
  * add maven plugin
  * Python plugin: added pygrep command, simplified pyclean
  * Fixed: If you callvim on a non-existant file with a relative path, the CWD of the running gvim process is used, and that's not right.  We use the PWD explicitly instead, in this case
  * A plugin that makes it easier to interact with the (single) running instance of gvim
  * Add a cat smilie as alias for cat
  * Don't clobber standard Esc+. behavior
  * Plugin for encoding strings into base64 and decoding them
  * added powed command to list pow urls
  * delete time filed
  * Disabled title function for emacs term mode
  * fix gnzh theme to detect local rvm installations
  * change color of @ to cyan
  * add hostname behind username, example: henryyan [02:07:20]  ~/.oh-my-zsh git:(master) ✗
  * move kafeitu.zsh-theme to themes folder
  * Added kafeitu theme it modified by robbyrussell
  * Added link to wiki page for plugins to README.
  * current repository action
  * Pager is 'less -R' to support colored outputs
  * Add dircycle plugin: enables cycling through the directory stack
  * made the 'd' alias only show the directories that can be cd'ed to using the number aliases
  * Add gem build autocompletion
  * clean up rbenv support for 'fino' theme
  * merge changes from offical repo
  * Fix spurious correction with sudo vim
  * Add completion for pip install -r - so that it autocompletes requirements filenames
  * Merge pull request #958 from cruser42/master
  * Fixed bug introduced when fixing issue 896
  * Merge pull request #868 from wgriffioen/bundler_add_rails
  * Merge pull request #925 from cruser42/bugfix/gitversionfix
  * [JM] Removed LSCOLOR Declaration for Wider Support
  * Added New Theme: sonicradish  (256 colors)
  * Added a peepcode theme
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * change the color of arrow when the command line return an error
  * blinks theme works with light and dark Solarized
  * handle case where ~/.rvm/bin/rvm-prompt is not in path, so "which" can't find it
  * fixed introduced to parse_git_dirty
  * changed variable PRE_1_7_2_GIT to POST_1_7_2_GIT to make it more accurate
  * fixed asterisk display for modified repos in git prior to 1.7.2
  * add default rbenv_prompt_info implementation to close #878
  * added "publish" and "track" command completion for git-flow plugin
  * Fixed Mac OS X Terminal.app related issue with extra newlines being printed out sometimes
  * Merge pull request #666 from szetobo/rails_runner
  * Removed trailing spaces in Git files. Fixes #867
  * update rails runner alias to ru
  * prompt git-remove as deleted
  * added rails to bundled_commands
  * Merge pull request #663 from gravof/patch-1
  * Merge pull request #850 from johnantoni/pow-fix
  * Merge pull request #860 from sbfaulkner/rbenv-support-for-themes
  * Merge pull request #865 from iltempo/patch-1
  * adding engine yard command (ey) to bundler binstubs
  * adding rbenv support to all the rvm themes
  * Merge pull request #845 from tjwallace/bundler_plugin_fix
  * Merge pull request #717 from blueyed/github-plugin-working-hub
  * Merge pull request #801 from kalos/autojump
  * Merge pull request #811 from markdrago/remove_verbose_mercurial_flags
  * Merge pull request #853 from lepht/master
  * Merge pull request #810 from cseeger/master
  * Merge pull request #856 from sgharms/patch-1
  * Merge pull request #858 from tatey/bundle_plugin_middleman
  * Add middleman to bundled commands
  * Grammar update
  * Fixed compdef alias to use 'gd' as shortcut.
  * Updated to latest version of taskwarrior completions (using Taskwarrior 2.0b4)
  * bug : stop creating those ~ directories add powit command to symlink an app if it hasn't been already
  * don't check for tmp dir
  * add alias to view the standard out (puts) from any pow app
  * take in csexton's changes
  * fix for pow plugin to default to current dir
  * Merge pull request #721 from gawel/master
  * Merge pull request #783 from oteyatosys/master
  * Merge pull request #830 from dbye/speedup
  * Merge pull request #847 from msharp/master
  * added a rake plugin to disable zsh file globbing when calling rake tasks with square brackets
  * fix bundler plugin for root level folders
  * Merge pull request #840 from arbovm/master
  * Merge pull request #838 from Bounga/bundled_thor
  * Merge pull request #833 from backspace/patch-1
  * fixing #812: adding plugins w/o plugin.zsh file to fpath.
  * Correct color and font issues on Ubuntu
  * Add Thor to bundled commands
  * Removed the assignments to fpath as well, since that's all handled in the .oh-my-zsh/oh-my-zsh.sh boot script.
  * sprunge-plugin: Remove the unnecessary while loop.
  * Fix the behaviour of the sprunge plugin so that is preserves whitespaces and tabs.
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Don’t report that Oh My Zsh has been updated when it hasn’t.
  * Removed calls to compinit in the extract and the bundler plugins. compinit should only be called once, after all modules, libs, etc are imported.
  * Merge branch 'master' into cloud_parameter
  * check if autojump is installed
  * Merge pull request #784 from lnxbil/967e84ebaa180ad2ab1eebc9a512f94d93e84aea
  * Merge pull request #806 from OutPunk/terminalapp-plugin
  * Kill the compdef; Introduce 'grh' alias for 'git reset HEAD'
  * Added alias for git diff.
  * Merge pull request #816 from lucapette/add-annotate-to-bundler-commands
  * add annotate
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh into cloud_parameter
  * remove the -v flag from a few mercurial aliases
  * Git Plugin: adds 'grhh' alias for 'git reset HEAD --hard'
  * Apple Terminal.app resume directory plugin
  * autojump plugin enhanced
  * Merge pull request #785 from simonjefford/patch-1
  * Merge pull request #799 from plindborg/ruby-plugin-fix
  * Fixed the rfind command in the  ruby plugin
  * Merge pull request #790 from cicloid/master
  * add ability to set custom prefix for cloud theme
  * Get the Hostname
  * bundler plugin - don't "bundle exec rails"
  * correctly handle path names with spaces
  * multiple versions could occur and should also be highlighted
  * Mortal Scumbag Theme
  * make pygmalion theme use two lines when needed
  * Added vsplit_tab and split_tab for iTerm. Create new session within a vertical/horizontal split of the tab respectively.
  * Merge pull request #679 from ornicar/official
  * Merge pull request #671 from peterhoeg/31cddcd32427a5f5d3daa0da168d39aba5b510b4
  * Merge pull request #688 from alexstrat/master
  * Merge pull request #693 from dreur/upstream-debian-apt-history
  * Merge pull request #702 from sirech/fix-bundle-compl
  * Merge pull request #710 from moutten/patch-1
  * Merge pull request #669 from peterhoeg/f/battery
  * Merge pull request #618 from fceccon/custom-theme
  * Updating installation documentation to show a curl example as well for those who don't have wget installed.
  * Merge pull request #776 from mytechnix/master
  * Merge pull request #747 from ilikenwf/1a49f6443c0230b8e182294546ed9ef2a5110bf2
  * Merge pull request #764 from Fl4t/submodules
  * Merge pull request #772 from indrajitr/master
  * Merge pull request #765 from trevor/master
  * Merge pull request #768 from askreet/master
  * Merge pull request #769 from divineforest/master
  * Merge pull request #775 from tatey/sammy_black_on_white_theme
  * Added example aliases in ZSH template. Added a new theme.
  * Black on white theme inspired by Sam Stephenson's terminal screenshot on https://github.com/sstephenson/rbenv
  * Fix upgrade and uninstall functions to pick up $ZSH value
  * Added alias gcm='git checkout master
  * Added support for entries in /etc/ssh/ssh_known_hosts.
  * Ignore submodules dirty in prompt info
  * add note about custom plugins
  * Merge pull request #752 from andrewtch/symfony2-completion
  * Merge pull request #757 from cwjohnston/knife-environments
  * Merge pull request #759 from Zhann/master
  * show gemset next to ruby version
  * adding support for chef environments in knife plugin
  * Symfony 2 completion
  * Merge pull request #708 from eatnumber1/update-print
  * `setopt append_history` is not necessary.
  * Only `setopt correct`, not "correct_all".
  * add sprunge.us pastebin uploader - uses files, or pipes
  * Merge remote branch 'upstream/master'
  * Fixes and improves the behavior of the tm command
  * Merge pull request #343 from giddie/plugin-wakeonlan
  * Merge pull request #743 from c089/autojump-macports
  * Merge pull request #741 from suvash/master
  * Merge pull request #738 from pygatea/master
  * Merge pull request #733 from Zhann/master
  * Merge pull request #732 from ggustafsson/patch-1
  * Merge pull request #734 from maxpersson/726-pip-completion
  * Merge pull request #709 from docwhat/custom-plugin-fpath
  * Merge pull request #707 from gmcmillan/master
  * Merge pull request #706 from docwhat/termsupport-hook
  * Merge pull request #701 from kirs/master
  * Merge pull request #553 from benlumley/master
  * add support for autojump installed via macports
  * Added my own theme file : suvash
  * forks miloshadzic theme to add more directory info as well as user and host info
  * Merge remote branch 'upstream/master'
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * Added message when caching packages
  * Added caching of packages
  * Added brute force package completin on install subcommand
  * Adding critical security patch to let you all know I'm on top of this shit. add 'nyan' to your plugins... then run  for security upgrade.
  * Added Zhann theme. Based on Robbyrussel theme, but shows the current ruby version and has some color variations.
  * Removed duplicate setting and sorted the remaining
  * Jake-node plugin : update - remove the need to write a `jake_tasks` in the directory - use most recent usage of completion with zsh - tested for MacOSX and Ubuntu
  * tmuxinator completion
  * allow django-manage completion. http://pypi.python.org/pypi/DjangoDevKit
  * Only alias git=hub if `hub --version` works.
  * Update theme
  * Add the --format tag to knife list commands
  * Moved ZSH_CUSTOM declaration before fpath is set
  * set fpath correctly for custom plugins
  * Use printf rather than echo -e in update.sh
  * Added option to disable the update prompt. Set DISABLE_UPDATE_PROMPT to true to enable.
  * Added add-zsh-hook support to themes
  * lib/termsupport now uses add-zsh-hook
  * FIX: commands like ruby and rake where not being completed
  * Rails Migrations support
  * Add apt-history to debian plugin
  * Update completion for SSH
  * Adding custom theme
  * minor modifications in comment header (the revenge)
  * Minor modifications in comment-header
  * Added completion plugin for jake
  * update fino theme to work with rbenv
  * Add yaourt --sucre alias in archlinux plugin
  * Add zsh_reload which provides src function, this function will source .zshrc and rebuilds cache
  * fix: rbenv: I need to find a proper way to test changes...
  * add: rbenv plugin
  * add: battery plugin
  * add rails runner alias
  * Replace "git-diff" with "git diff" in the git plugin
  * RVM info
  * FrontCube theme with git status
  * Update the script to account for the changes in 0.1.7 where .gas is a directory
  * Do not overwrite EDITOR environment variable if already defined.
  * Comment
  * Merge remote-tracking branch 'upstream/master' into emacs
  * Fix builtin `ecd' when file path contains space characters.
  * Merge pull request #505 from masnick/master
  * Merge pull request #529 from dbb/master
  * Merge pull request #552 from Tricon/master
  * Merge pull request #579 from hakanensari/bundler-plugin-patch
  * Merge pull request #594 from sirech/fix-bundle-compl
  * Merge pull request #595 from zachriggle/grails-plugin
  * Merge pull request #554 from toolbear/549-fix-auto-upgrade
  * Merge pull request #607 from vddgil/patch-1
  * Merge pull request #613 from rkj/master
  * Merge pull request #614 from philippbosch/feature/terminitor-plugin
  * Merge pull request #622 from foozmeat/master
  * Merge pull request #626 from nickstenning/upstream
  * Merge pull request #631 from danshearmur/git-merge-alias
  * Merge pull request #645 from mr-szymanski/master
  * Merge pull request #648 from SFEley/d926a55872b5a12ab8b987e9d86c02358d0c825e
  * Merge pull request #418 from ptrv/master
  * Merge pull request #441 from Gonzih/master
  * Merge pull request #273 from blueyed/hub-alias-only-with-ruby
  * Merge pull request #225 from Soliah/plugin-bundler
  * Merge pull request #205 from sorin-ionescu/plugin-gnu-utils
  * Merge pull request #482 from volpino/master
  * Merge pull request #428 from matthewmccullough/gradleplugin
  * Merge pull request #338 from norm2782/master
  * Merge pull request #319 from sorin-ionescu/plugin-npm
  * Merge pull request #275 from tristan0x/require_tool
  * Merge pull request #274 from diofeher/master
  * Merge pull request #525 from kibs/master
  * Change default zshrc to export $ZSH (as required by check_for_upgrade.sh).
  * Fix up some wonkiness
  * Add new theme: wuffers
  * Show if you're ahead of remote in the wedisagree theme
  * added git merge as gm
  * Better cake completion: don't barf on options, and don't clobber user's namespace
  * This is the correct way to check the return value
  * This needs to explicitly check the return value
  * First search in the custom folder for the theme
  * Adding README file for the wakeonlan plugin
  * split rkj into two themes.
  * Splitting wakeonlan plugin completion into separate file
  * Forgot to quote the path parameter to wakeonlan
  * Tweaks to the wakeonlan plugin
  * terminitor plugin: add autocompletion also for edit, delete and setup subcommands.
  * terminitor plugin: add autocompletion for start subcommand.
  * Add basic autocompletion for terminitor (https://github.com/achiu/terminitor).
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * Textmate plugin update to take Gemfile and cucumber features in account
  * Added VCS prompt to Apple theme.
  * [plugins/grails] Remove warning message; it's always displayed
  * [plugins/grails] Use globbing instead of grep
  * [plugins/grails] Added grails plugin
  * fix completion for commands wrapped with bundler
  * New function `efile`
  * Merge branch 'master' of github.com:Gonzih/oh-my-zsh
  * vundle call fixed for new vundle version
  * add foreman, nanoc, and rainbows to list of bundled commands
  * order aliases alphabetically
  * Merge pull request #490 from hwti/428f18cf428fd86bd6e99c4363e5f25d0e392506
  * Merge pull request #408 from thunfischbrot/patch-1
  * Merge pull request #575 from mr-szymanski/master
  * Revert "Enable red dots during completion by default".
  * Add an alias for ga --> git add, too
  * Add gss alias for git status -s
  * Fix auto upgrade failure from non-exported ZSH env var
  * Rename to _capistrano (completion only)
  * Gallois theme - made the git branch/status show for those of us without rvm
  * Added nifty purple Apple theme.
  * Remove -s switch from apt-copy
  * oops, restore broken theme preview
  * detect rvm or rbenv and show ruby version
  * Merge pull request #545 from ches/patch-1
  * Add guard to bundler plugin's wrapped commands
  * Merge pull request #543 from dmondark/heroku-completion
  * Added a gradle build tool plugin
  * Heroku completion plugin
  * Merge pull request #492 from hwti/red-dots-completion
  * Merge pull request #512 from ichesnokov/master
  * Merge pull request #515 from rahult/feature/powder-plugin
  * Extend root ops, switch apt-copy to plain zsh
  * Add options for su(do) and apt(itude|-get)
  * Add functions for new GH repos.
  * Add functions for new GH repos.
  * Fix su commands
  * Merge "deb" and "debian" plugins.
  * Add bundle open alias, which open gem using EDITOR var
  * added option of setting another path to custom plugins and files
  * fixed theme chooser + options + list available themes + show all themes
  * add theme with command-line tips support
  * Added auto complete plugin for powder gem https://github.com/Rodreegez/powder
  * Fix edit-command-line binding
  * Merge in recent stuff
  * 'echo' did not show colors without -e in upgrade.sh
  * Merge pull request #464 from bkonkle/patch-1
  * Merge pull request #507 from walle/add_autocomplete_for_gas
  * Replace forgotten rubies with authors
  * Add autocomplete for gas. Based on the rvm plugin.
  * Add fino.zsh-theme
  * Enable red dots during completion by default
  * Merge pull request #494 from EspadaV8/master
  * Merge pull request #496 from semmons99/master
  * Merge pull request #502 from sunaku/history
  * move history-substring-search* files into plugins/
  * add alias for `bundle package` to the bundler plugin
  * The original SVN pluging would mark a folder as dirty if there was an svn:external set and the output of 'svn status' returned the check for the external. E.g.
  * Replace a duplicated test to see if we're in an SVN folder with a call to the 'in_svn' function.
  * Display red dots during completion process (disabled by default)
  * global zsh config
  * mac os fix
  * Add key bindings for gnome-terminal on Fedora
  * Merge pull request #488 from dreur/upstream-archlinux-plugin
  * Merge pull request #259 from dereine/master
  * Merge pull request #251 from kalasjocke/master
  * Merge pull request #215 from sunaku/history
  * Merge pull request #208 from sorin-ionescu/plugin-extract
  * Merge pull request #206 from sorin-ionescu/plugin-osx
  * Merge pull request #167 from jarinudom/master
  * Merge pull request #112 from lukerandall/master
  * fixing issue with last commit merge. missed a conflict
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * adding git svn aliases
  * added git log with graph
  * added mac keybinding for backward-delete-char
  * Merge pull request #412 from transat/master
  * Merge pull request #461 from dpoggi/master
  * Merge pull request #487 from dreur/upstream-spectrum-utility
  * More generic.
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Don't export oh-my-zsh configuration paramaters to the environment
  * Merge pull request #107 from philips/philips-theme
  * Merge pull request #484 from msabramo/f9bf396e4ac68299f1370ed54350cc14ce954eea
  * Remove sudo when using yaourt + do not rely on abs when not in path - In archlinux plugin
  * Add utility method to spectrum
  * Merge pull request #483 from dreur/upstream-archlinux-plugin
  * Fix typo
  * fox's theme + theme chooser fixes
  * added theme chooser
  * Merge pull request #480 from PabloSerbo/master
  * Bringing inline with oh-my-zsh coding convensions
  * Merge pull request #479 from csexton/edit-command-line
  * C-x C-e to edit current command in EDITOR
  * Merge pull request #474 from PabloSerbo/master
  * Merge pull request #476 from theunraveler/master
  * Merge pull request #452 from franklouwers/master
  * Merge pull request #468 from blinks/master
  * Merge pull request #477 from totolici/patch-1
  * Merge pull request #404 from gwjo/ssh-agent
  * Merge pull request #415 from eproxus/master
  * Merge pull request #475 from dreur/upstream-archlinux-plugin
  * Fixed typo for one of the subcommands (linset -> linsert)
  * Adding quotes to deal with paths that have spaces.
  * Added archlinux plugin
  * Completion for cake the coffee-script build tool
  * rsync: add rsync- prefixes and use aliases
  * Merge pull request #370 from lepht/taskwarrior-plugin
  * Merge pull request #451 from matthewmccullough/cloudappplugin
  * Merge pull request #467 from papercavalier/bundler
  * zsh-history-substring-search plugin at 15f63de
  * Added a new theme.
  * refactor _run-with-bundler
  * Minor corrections to deletion detection in git_prompt_status
  * Merge pull request #462 from papercavalier/bundler
  * clean up rails plugin, removing bundler-specific logic
  * alias bundle list
  * merge bundler and bundle-exec plugins
  * fix indentation
  * update bundled commands
  * Moved opening braces
  * forgot to rename one variable
  * changed names of functions and variables to fit naming conventions
  * use lowercase for variablenames
  * Added bundler-exec plugin
  * Added 'dpoggi' theme
  * knife autocompletion
  * added tip about vundle configutarion after git clone
  * vundle plugin refactored first it checks existens of vundle plugin, if plugin dont exist run git clone
  * Added cloudapp from @holman of @GitHub fame
  * Merge remote-tracking branch 'robbyrussell/master'
  * Updated the frisk theme to display Bazaar branch information as well (based on zedtux.zsh-theme http://j.mp/ikTZJj)
  * removing useless line
  * plugin for vundle (vim plugins managment system) that provide vundle, vundle-update and vundle-init aliases
  * Create gnzh theme
  * Merge pull request #429 from mhitza/master
  * Merge pull request #436 from smt/pull-request-1
  * Changed kanji to fuku (good luck)
  * Add ohmyzsh theme, my version of dogenpunk
  * rsync: add plugin
  * When the theme choice is left out, oh-my-zsh will not try to load it
  * use /home/ryan/d/.oh-my-zsh instead of ~/.oh-my-zsh for cache
  * Added mercurial plugin with aliases.
  * Add Django plugin. This is a slight modification of the Django zsh completions that I found at https://raw.github.com/technolize/zsh-completion-funcs/master/_manage.py
  * Fix MM lines being read correctly
  * Change plugin name from cap to capistrano
  * Rename guru theme to sunrise
  * Fix git R and M status when used together
  * Add note about Solarized color theme
  * Add email address
  * Merge remote-tracking branch 'robbyrussell/master'
  * Remove unused colors and use original prompt color
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Dollar sign instead of percent in unprivileged user prompt (as in real gentoo)
  * Included some essential aliases, inspired by http://lolcode.com/
  * New theme, Read contents for further customising.
  * Aliases
  * Merge pull request #400 from mkomitee/master
  * Add support for loading mulitple identities
  * Add support for agent forwarding
  * Fix bug from Pull request #395     #395 broke oh-my-zsh for users who disable check-for-updates
  * Merge pull request #395 from vguerci/upgrade-before-init
  * [upgrade] before init (no reload needed unless oh-my-zsh.sh has been modified)
  * Colorize Install & Upgrade Scripts
  * Merge pull request #371 from nebirhos/master
  * Merge pull request #378 from secondplanet/master
  * Merge pull request #391 from mattdoran/master
  * Fix typos in the svn plugin that would cause calls to 'svn' when not in an svn working copy.
  * Merge pull request #385 from sunaku/theme
  * add "sunaku" theme, see http://ompldr.org/vOHcwZg
  * Added gnu-utils plugin.
  * Handle tar.xz and tar.lzma better (credit: @gwjo).
  * Added extract plugin.
  * Added man-preview completion suggested by @webflo.
  * Vastly improved osx plugin.
  * Replaced npm 0.x completion with 1.0 completion.
  * Merge pull request #382 from miloshadzic/master
  * Merge pull request #380 from brianjriddle/master
  * Merge pull request #383 from alanpeabody/master
  * Adds my theme
  * Remove extra space when no status
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Revert "Added my zsh theme file, heavily based on sjl's" as it relies on a dotfile to be in ~/bin.
  * Merge pull request #375 from betawaffle/rollback-366
  * Merge pull request #381 from thePapacy/fix-git-zsh
  * Fix deleted in git.zsh
  * fix double -f and corrected format.
  * Improve unicode characters and git status
  * Add guru theme
  * added humza.zsh-theme
  * Remove Uneeded Lines
  * Rollback of Pull #366
  * Added nebirhos theme
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh into taskwarrior-plugin
  * Merge pull request #359 from theunraveler/master
  * Merge pull request #363 from Blattlaus/master
  * Merge pull request #366 from betawaffle/master
  * Merge pull request #368 from trapd00r/master
  * Merge pull request #365 from briankftse/master
  * add trapd00r theme
  * Fixed cap plugin
  * Merge branch 'plugins'
  * Thor
  * Cleanup
  * Add new 'minimal' theme
  * OS X Helpers
  * Node.js Helpers
  * Pow! Restart Helper
  * Brew Plugin
  * Gem List Helper
  * RVM Update Helpers
  * Helpful Listing Aliases
  * Ruby Switching Helpers
  * Added compatibility for the linux 'stat' command for the ant plugin
  * Added my own theme.
  * Adding ability to override plugins from the custom directory.
  * Merge pull request #345 from jacobat/master
  * Merge pull request #346 from jojahner/master
  * Merge pull request #196 from asymmetric/master
  * Merge pull request #226 from sunaku/fishy
  * Merge pull request #139 from clauswitt/master
  * Merge pull request #118 from fwalch/gpg-agent
  * Merge pull request #92 from re5et/master
  * Merge pull request #90 from steeef/steeef-theme
  * fishy theme: text indicators for $? and git status
  * Merge pull request #351 from GutenLinux/master
  * Merge pull request #347 from obcode/master
  * Merge pull request #355 from watsoncj/master^1
  * Adds oh-my-zsh plugin to load TaskWarrior completions
  * Adds the _task script included with TaskWarrior
  * Adds compl .swp caches to gitignore
  * Fix to random theme selection
  * Merge pull request #224 from Soliah/plugin-rvm
  * add custom completion support
  * Added obraun theme which is a slightly modified version of an already existing theme.
  * Added 'simple' theme.
  * Update, no more full path
  * TextMate automatically forks into the background
  * Add autojump plugin
  * Plugin to make WOL nice & easy
  * Add norm theme
  * Merge pull request #295 from alexrinass/apache2-macports-plugin
  * Merge pull request #290 from arthurkalm/delete-key-working
  * Merge pull request #322 from jonashuckestein/master
  * Merge pull request #324 from sorin-ionescu/plugin-compleat
  * Merge pull request #329 from juanghurtado/master
  * Merge pull request #330 from jtriley/jtriley-theme
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * remove git status from prompt
  * Adds support for $(current_branch) on git_parse_ahead()
  * Added Compleat - Completion for Human Beings plugin.
  * added my theme
  * Merge pull request #321 from nel/fix-window-title-regex.
  * Relax pattern matching on TERM. Closes #320.
  * Merge pull request #314 from mattsacks/master.
  * Merged pull request #315 from nebirhos/master.
  * Add fine-grained git prompt status to lukerandall.zsh-theme
  * fixed autoupdate
  * Add muse theme for 256 color terminals
  * Merged pull request #312 from juanghurtado/master.
  * Custom theme with Git support
  * Merged pull request #310 from Ikke/master.
  * Merged pull request #270 from sankara/d03a6176aacd583993c02c7e837d10751c431875.
  * Merged pull request #311 from papercavalier/rails3.
  * Rails 3 aliases now work with Rails 2 as well.
  * Added git-flow plugin
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Feature: Random themes now supported. Just set your theme to 'random' and it'll load a different theme each time oh-my-zsh is started. Closes #309
  * Merged pull request #308 from juanghurtado/master.
  * Adds new prompt methods on Git lib
  * Merged pull request #307 from jtriley/jtriley-theme.
  * Merged pull request #302 from JonathanTron/5bcfab37312511a7ffc3e8242ba8b8a622ecf061.
  * Merged pull request #303 from cit/master.
  * Merged pull request #299 from atmos/master.
  * Merged pull request #269 from oknowton/master.
  * Move sourcing of custom to below plugins
  * add my custom zsh prompt
  * add git-prompt plugin from olivierverdier/zsh-git-prompt
  * redis-cli.plugin.zsh removed, adding to the fpath isn't needed now
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * added alias for apt-cache search
  * Merged pull request #138 from murilasso/master.
  * Merged pull request #276 from saimn/yum.
  * Merged pull request #278 from totolici/redis-plugin.
  * Merged pull request #288 from dogenpunk/dogenpunk_theme.
  * Merged pull request #287 from arthurkalm/install-tweeks.
  * Merged pull request #294 from alexrinass/mysql-macports-plugin.
  * Merged pull request #297 from Soliah/master.
  * Merged pull request #298 from wolverian/master.
  * Merged pull request #300 from gallois/master.
  * added custom theme, based on eastwood
  * support non-standard rvm install prefixes
  * Add 'upgrade' to brew completions.
  * Made my them display the current rvm gemset and check for detached head state in git.
  * Added start/stop aliases for Apache 2 installation via macports.
  * Fixed folder naming for mysql-macports plugin and improved start/stop scripts.
  * Remove fpath/compinit code from github and npm plugins
  * Merge remote branch 'upstream/master'
  * Added bindings for Gnome terminal.
  * Make the delete key work correctly, instead of outputting a ~
  * Changed to use which.
  * Change URL to https since most corporate environments block git port.
  * Make the chsh more reliable.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Add new jonathan theme
  * Fix indentation
  * Fix alias `eeval'
  * - Fix pass of parameters - Add new function `ecd'.
  * redis-cli completion plugin
  * refactored pycrm command
  * More comments
  * I should not have merged this here.
  * new yum plugin with useful aliases
  * Removing master stuff
  * Merge branch 'master'; commit 'ca4dabb45e14d8cd38e07c4ffadf9473ceb2193b' into require_tool
  * Add new plugin emacs, to take benefit of daemon capabilities of emacs >=23
  * Fix version parsing. Now working with command $ zsh --version
  * New tool require_tool.sh
  * adding python plugin with some aliases
  * New plugin git-svn installing git project git-svn-clone-externals
  * Minor reformatting
  * github plugin: check for `ruby`.
  * Moved the plugin fpath loop and compinit so they happen before custom scripts are loaded.
  * Optimize plugin loading so that only one call to compinit is required
  * Moved compinit call back to oh-my-zsh.sh, after plugins are loaded
  * Add: new theme
  * Merge branch 'friskTheme' of https://github.com/Nycto/oh-my-zsh
  * Added the Frisk theme
  * Updating the README... now links to contributors page
  * kolo.zsh-theme
  * changes recommended by blueyed
  * Whoops, this was supposed to be in the last commit!
  * Moved this to the existing github plugin
  * blueyed's ZSH-fu is much stronger than mine.
  * no need for an extra fork
  * added hub plugin from defunkt
  * Revert "Enable alias completion, do not limit completion to just files"
  * Added npm plugin.
  * Using git-diff instead of git diff
  * Removing call to mate.
  * Fix `gdv`: make it a function, and use `view`.
  * Removed commented out code.
  * Moved the single compinit call from oh-my-zsh.sh to lib/completion.zsh
  * Replace redundant calls to compinit with a single call.
  * Refactor DISABLE_AUTO_TITLE to be more DRY
  * Command title behavior no longer depend on local zsh configuration
  * Escape characters used in escape sequence to avoid triggering bugs in Apple Terminal
  * Further git completion improovements
  * Completions are git subdommand-aware now
  * Zsh will now complete git aliases with git stuff
  * Merge branch 'disable_auto-title' of https://github.com/lorrin/oh-my-zsh into lorrin-disable_auto-title
  * Adding dogenpunk theme
  * Add a plugin to support kate the kde texteditor
  * fixed wget command in readme
  * Introduce DISABLE_AUTO_TITLE option
  * Make command-not-found no-op when support not available (e.g. not on Ubuntu)
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Lein completion
  * New theme 'intheloop' which demonstrates the git_remote_status function
  * Added new function git_remote_status to check if we are ahead, behind or diverged from the remote branch
  * Added terminal party theme.
  * Added the Frisk theme
  * Revert "Re-order title/tab setting to make window titles work on OSX terminal which" Was causing iTerm title to disappear entirely..
  * Merge branch 'ssh-agent-append-host-to-environment' of https://github.com/trcjr/oh-my-zsh into trcjr-ssh-agent-append-host-to-environment
  * Merge branch 'master' of https://github.com/AlexBio/oh-my-zsh into AlexBio-master
  * Merge branch 'osx-terminal-title' of https://github.com/curiousstranger/oh-my-zsh into curiousstranger-osx-terminal-title
  * Merge branch 'master' of https://github.com/dbbolton/oh-my-zsh into dbbolton-master
  * Merge branch 'feature/alias-completion' of https://github.com/shadowhand/oh-my-zsh into shadowhand-feature/alias-completion
  * Merge branch 'master' of https://github.com/tjkirch/oh-my-zsh into tjkirch-master
  * Add debian plugins file
  * No space before prompt char at beginning of line
  * Actually show return code on failure
  * Sweet lightning bolt on uncommitted git changes
  * Remove unnecessary whitespace
  * Make personal theme based on dst
  * add Perl plugins file
  * Re-order title/tab setting to make window titles work on OSX terminal which doesn't support tabs titles.
  * Add completion for port command
  * add 'deb' plugin with Debian's apt aliases
  * add completion plugin 'cpanm' for cpanminus
  * add 'lol' plugin (based on lolbash)
  * Enable alias completion, do not limit completion to just files
  * Merge ssh://spix-dev01/home/fredrik/.oh-my-zsh
  * figuring out home dir on unix systems as well
  * Merge branch 'master' of github.com:fred-o/oh-my-zsh
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * fix to avoid parse errors if $TERM is empty
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * Added a plugin for GNU Screen.
  * .gitignore
  * ssh-agent plugin now ends in "-$HOST" so an agent is started properly with nfs shared homes.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of git@github.com:fred-o/oh-my-zsh
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Refined RVM prompt in Crunch theme
  * Crunch theme (by Stephen Eley)
  * Add tab completion to bundler plugin.
  * Add tab completion for rvm.
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * no hg & git status (sloooow)
  * Merge branch 'master' of https://github.com/myronmarston/oh-my-zsh into myronmarston-master
  * Merge branch 'refactor-term' of https://github.com/nel/oh-my-zsh into nel-refactor-term
  * Merge branch 'master' of https://github.com/medwezys/oh-my-zsh into medwezys-master
  * Merge branch 'osx' of https://github.com/benlangfeld/oh-my-zsh into benlangfeld-osx
  * Merge branch 'master' of https://github.com/Soliah/oh-my-zsh into Soliah-master
  * Merge branch 'lib-git' of https://github.com/sorin-ionescu/oh-my-zsh into sorin-ionescu-lib-git
  * Merge branch 'master' of https://github.com/nanotech/oh-my-zsh into nanotech-master
  * Merge branch 'theme-sorin' of https://github.com/sorin-ionescu/oh-my-zsh into sorin-ionescu-theme-sorin
  * Merge branch 'master' of https://github.com/Nemo157/oh-my-zsh into Nemo157-master
  * Merge branch 'nicoulaj-theme' of https://github.com/nicoulaj/oh-my-zsh into nicoulaj-nicoulaj-theme
  * Add iTerm version of tab function (itab)
  * Make a cleaner version of the OS X tab function
  * Renamed theme.
  * Added my theme.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * mvn plugin
  * Add bundler plugin with aliases.
  * Should use https for all GitHub urls.
  * fixed typo in rails3 plugin and added one alias for migrating and redoing migration if it was successful
  * Merge branch 'master' of github.com:fred-o/oh-my-zsh
  * Add vagrant completion for individual VMs
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * Added modified while newly added and type change detection to git prompt modified status.
  * Fixed auto update.
  * Added sorin oh-my-zsh theme.
  * Added time since last commit to Soliah theme and changed some colours.
  * Refactor window and tab title in tty
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * add missing unrar flag
  * Merge branch 'master' of https://github.com/theunraveler/oh-my-zsh into theunraveler-master
  * Merge branch 'master' of https://github.com/SuprDewd/oh-my-zsh into SuprDewd-master
  * Merge branch 'postpone-theme-sourcing' of https://github.com/mkomitee/oh-my-zsh into mkomitee-postpone-theme-sourcing
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of https://github.com/Rixius/oh-my-zsh into Rixius-master
  * Merge branch 'dieter-theme' of https://github.com/Dieterbe/oh-my-zsh into Dieterbe-dieter-theme
  * Merge branch 'typo' of https://github.com/papercavalier/oh-my-zsh into papercavalier-typo
  * Merge branch 'master' of https://github.com/sunaku/oh-my-zsh
  * Merge branch 'master' of https://github.com/dannytatom/oh-my-zsh into dannytatom-master
  * Merge branch 'master' of https://github.com/flazz/oh-my-zsh into flazz-master
  * added newline
  * Personal Style
  * theme changes
  * changes to theme
  * add Rixius-Theme
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Added an option to remove file afterwards.
  * Added svn info in prompt with plugin.
  * Made git ignore everything  in custom, not only the .zsh files.
  * theme based on afowler with vi-mode support
  * Added lambda theme
  * Postponing sourcing of the theme until after local customizations
  * avoid forking subshell to test if user is root
  * Merge branch 'git' of https://github.com/papercavalier/oh-my-zsh into papercavalier-git
  * Merge branch 'master' of https://github.com/derekprior/oh-my-zsh into derekprior-master
  * Merge branch 'rails3' of https://github.com/papercavalier/oh-my-zsh into papercavalier-rails3
  * add "fishy" theme to emulate Fish shell's prompt
  * Support for more archive formats.
  * Added a function to extract various archives. Also an alias for the function.
  * Added function to mkdir and immediately change to it
  * Add superjarin theme that shows current Ruby version via RVM
  * Typo
  * Removed remote_console. It doesn't handle rvm, capistrano, and so on.
  * A rails3 plugin based on the rails plugin
  * Aliased git checkout as `gco`
  * Fixed typo
  * Updating theunraveler theme to include more detailed git info.
  * Merge branch 'kardan' of https://github.com/kardan/oh-my-zsh into kardan-kardan
  * Updated the PROMT.
  * Added new kardan theme.
  * gentoo-like theme w/ git_prompt_info
  * Don't export oh-my-zsh configuration paramaters to the environment
  * maven plugin
  * Merge branch 'master' of github.com:clauswitt/oh-my-zsh
  * Added ant plugin
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * better phrasing/documentation
  * reset exit code visual cues (not exit code itself) after showing once
  * add dieter theme v1
  * Merge branch 'master' of https://github.com/robbyrussell/oh-my-zsh
  * Avoid duplicate path cropping
  * Add my prompt theme
  * Rename appearance.zsh so that it gets loaded after spectrum.zsh. Allows to use 256 colors in prompt themes.
  * changes
  * Merge branch 'fix-lighthouse-error-message' of https://github.com/mortice/oh-my-zsh into mortice-fix-lighthouse-error-message
  * Merge branch 'completions' of https://github.com/gwjo/oh-my-zsh into gwjo-completions
  * Merge branch 'joerc' of https://github.com/sargas/oh-my-zsh into sargas-joerc
  * Merge branch 'master' of https://github.com/Bira/oh-my-zsh into Bira-master
  * Merge branch 'master' of https://github.com/FedyashevNikita/oh-my-zsh into FedyashevNikita-master
  * Removed the echo statement - no need for that.
  * improved formatting; redundant attributes deleted
  * fixed formatting; dead code deleted
  * vagrant plugin autocompletion - initial version
  * themes/nanotech: Use the new built-in zsh color variables.
  * Added my own theme, based on macovsky-ruby and funky
  * Added phing plugin
  * Merge remote branch 'origin/master' into gpg-agent
  * Completion fixes
  * Fix lighthouse plugin error message
  * command-not-found package in ubuntu
  * merge from master
  * merge theme fixes from master
  * merge with master
  * merge with master
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Added gpg-agent plugin
  * Merge branch 'master' of http://github.com/robbyrussell/oh-my-zsh
  * Added own theme (based on robbyrussell)
  * themes: philips customize git/ls for developers
  * merging in changes from robby's repo
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * bugfix - moved gem info
  * Merge branch 'master' of http://github.com/svnlto/oh-my-zsh into svnlto-master
  * Merge branch 'master' of http://github.com/philtr/oh-my-zsh into philtr-master
  * Merge branch 'philips-theme' of http://github.com/philips/oh-my-zsh into philips-philips-theme
  * Merge branch 'title-fix' of http://github.com/philips/oh-my-zsh into philips-title-fix
  * changeing unicode characters that were causing issues
  * leaving out subcommands for now
  * adding comment and URL to github gem
  * added git log incl. stats for the past 5 commits
  * adding github plugin
  * themes: add philips theme
  * functions: fix title() to not match any $TERM
  * Fixing some minor redrew issue
  * Adding new gozilla theme
  * Improving git plugin so it can display much more data.
  * Add cloud.zsh-theme
  * merge master
  * use 256 colors, if available
  * should have newline at end of file.
  * adding my zsh-theme
  * added rkj theme - xion-chiamiov-plus + hg from thomasjbradley
  * fix untracked files checking
  * merge steeef.zsh-theme from master (removed submodule check)
  * merge steeef.zsh-theme from master
  * Removing capistrano aliases/functions from rails plugin (since cap is not rails-specific).
  * Add lukerandall.zsh-theme
  * adapt brew,gem,pip plugin to new structure
  * Merge remote branch 'origin/master' into restructure_plugins
  * Reorganizing plugins so that each plugin has it's own directory now so that any plugin-specific functions can be bundled within there.
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Merge branch 'master' of http://github.com/kennethreitz/oh-my-zsh into kennethreitz-master
  * Merge branch 'master' of http://github.com/vivekprahlad/oh-my-zsh into vivekprahlad-master
  * Merge branch 'dirpersist' of http://github.com/curiousstranger/oh-my-zsh into curiousstranger-dirpersist
  * Match xterm-color, the default OS X terminal
  * Tidying up the spacing to bring in line with coding standards
  * Merge branch 'ssh-agent' of http://github.com/gwjo/oh-my-zsh into gwjo-ssh-agent
  * Merge branch 'theunraveler_theme' of http://github.com/theunraveler/oh-my-zsh into theunraveler-theunraveler_theme
  * Merge branch 'named_dirs_completion' of http://github.com/kremso/oh-my-zsh into kremso-named_dirs_completion
  * Merge branch 'shifttab' of http://github.com/kremso/oh-my-zsh into kremso-shifttab
  * added steeef theme
  * Portable perl dirpersiststore because 'tail -r' doesn't work everywhere.
  * Add vi-mode plugin for vi-like editing
  * Do not complete named-directories
  * unset config_file is useless
  * Added theunraveler theme.
  * ssh-agent module
  * Removed unportable (and unnecessary) grep flags
  * Change zdirstore to variable
  * Added install instructions
  * Added installation function
  * Move dirpersist to plugin
  * Escape some metachars that trip up .zdirstore script
  * Escape &'s in path name.  Need to find general function for escaping all shell metacharacters.
  * Alias popd to remove deleted dirs from persistance
  * Initial pass at pesistant directory stack
  * Adding comments
  * Adding a plugin with aliases for macports
  * Merge branch 'pip_plugin'
  * Merge branch 'gem_plugin'
  * Merge branch 'brew_plugin_fix'
  * add pip completion and plugin
  * add gem completion function and plugin
  * Added the truly epic kennethreitz theme.
  * Removing '.' alias as it is overwriting a bash/zsh feature. Closes #63
  * fix problems with brew completion
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Switching to /usr/bin/env zsh instead of /bin/zsh in the installer
  * add fletcherm theme; a slightly modified copy of an old tonotdo theme
  * add simple mrtazz theme based on robbyrussell
  * update brew plugin from homebrew contributions
  * Merge branch 'master' of http://github.com/AlexBio/oh-my-zsh into AlexBio/master
  * Made the user_machine_size calculation generic. Pwned the function name.
  * Added my own theme based on pat's
  * add candy theme
  * Added my theme (nanotech).
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Adding a ggpnp which does a git pull followed by a git push.
  * updated the readme
  * added plugin to control macports mysql-server installation
  * Added my own theme.
  * Don't correct hpodder commands.
  * Added a minimum zsh version note.
  * Don't display dotfiles or reverse sort with ll alias.
  * Ignore commands that start with a space.
  * Don't auto-correct ebuild commands.
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Adding some candy to the upgrade script
  * Moving brew functions to it's own plugin
  * Moving current_branch() to git plugin
  * Moving some rails and osx-specific functions to their corresponding plugin files
  * Removing legacy completion code
  * Removing rake completion from lib/ as it was moved to rails plugin
  * Moving capistrano functions to rails plugin
  * Updating default .zshrc template file to include plugins declaration
  * Initial implementation of a new plugin system, so that people can managed which aliases/functions they want.
  * Eastwood theme with optional RVM support
  * adding my zsh theme -- only difference from robby's being that i'm using white instead of blue for legibility over brown
  * Added customized version of the wezm theme (mainly added username/host in the prompt).
  * Added my zsh theme file, heavily based on sjl's
  * aussiegeek theme (include showing rvm prompt)
  * Import rvm prompt
  * macowsky modified theme with ruby version on prompt
  * modified macovsky to support ruby version
  * Adds a new theme that only seems to work on Linux
  * Sprinkling some candy on this muffin.
  * added skaro theme
  * added my theme
  * New theme "daveverwer", based on "geoffgarside".
  * added my own theme
  * happy with my theme. caret turns red for root
  * my WIP theme
  * Added my own theme.
  * Add my preferred prompt
  * added the dstufft theme (based on prose by sjl)
  * Add my oh-my-zsh theme
  * share history with your zsh's on the same host
  * added my theme, based on xiong-chiamiov-plus but using vcs_info instead of just git
  * two aliases set to 'ss', clobbering rails script/server
  * my theme
  * Merge branch 'master' of github.com:robbyrussell/oh-my-zsh
  * Merge remote branch 'NV/master'
  * Adds new duellj theme
  * Merge remote branch 'jreese/master'
  * updated my theme with the date and git branch (+ dirty or not)
  * Merge remote branch 'robbyrussell/master'
  * Unsetting config_file after loading config
  * Don't autoselect first completion entry (Fixes #14)
  * Removing rake autocompletion as this is apparently  baked into recent versions of zsh
  * Fixed color in last character of clean git info
  * 256 color theme with bright blue and orange
  * escape sequences so rprompt doesn't mess up
  * Added scpectrum script for easy 256 color theaming
  * makes git status prompt 4x faster
  * Ignore errors from compaudit when using `sudo -s`
  * Remove limit of two segments to PWD
  * Added screenshot link for jreese theme
  * Added theme "jreese" to oh-my-zsh
  * Make Shift+Tab move backwards in the menu
  * added my personal theme: the dallas them
  * git:(master) --> git:master Parenthesis removed
  * Arrow theme: http://elv1s.ru/i/zsh-arrow-theme.png
  * clean theme: username is now bold
  * improvements to the 'clean' theme
  * added "clean" theme
  * fork xiong-chiamiov theme for git support
  * Putting Git related aliases into git.zsh to have them in context.
  * adding quotes to tab()
  * Adding a function that will open up a ticket in Lighthouse based on the number and there being a URL in a hidden file.
  * Adding a nocorrect for the heroku command as it was getting triggered by heroku logs.
  * Based on a suggestion from robbyrussel, using env for greater compatibility.
  * Instead of using the user's standard shell, this script should be run using zsh, since that was the shell it was written for.  On my machine changes to my default shell only take effect when I log out and then long in again.  Plus, it's nice for people to be able to try oh-my-zsh out even if zsh isn't their default shell right?  :-)
  * Merge commit 'e429ff9e2bed41f88e3df3315b159fa79a7152fc'
  * Merge branch 'master' of git://github.com/macovsky/oh-my-zsh into macovsky/master
  * Updating check_for_upgrade script to fix issue when the LAST_EPOCH file/value got corrupted. Closes #32
  * no correction on gist
  * new theme
  * No correction on mkdir + removed duplicate nocorrect mv
  * Revert
  * Completion from history
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Adding current_branch function, which can be used like: git pull origin master
  * tonotdo theme: Back to the original
  * tonotdo theme still not like I wanted
  * tonotdo theme like I like it
  * Theme tonotdo upgrade
  * Gallifrey theme
  * gave credit to Nick for the rake autocompletion code.
  * Spiced up the tonotdo theme, some more
  * Spiced up the tonotdo theme
  * LS_COLORS fix for tonotdo theme
  * Improved the LS_COLORS in my tonotdo theme
  * Fixed all themes so tab-completion doesn't move the cursor to a weird position
  * Modifying changes for issue 25, to fix issue 27
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Revert "Added my prompt theme, with a tweak to the core oh-my-zsh to support it. My git_prompt_info function not only reports the branch and dirty status, but also whether or not the branch is ahead or behind of the remote, or both. It also switches the prompt colour from green to red if the previous command exited with a non-zero value (i.e. failed)."
  * Revert "Whoops, forgot to include this dummy precmd implementation."
  * Only using the contents of .ssh/known_hosts when the file exists for ssh/scp auto-completion. Closes issue #20
  * Removing gdb alias as it conflicts with an actual command for gdb. Closes #17
  * Revert "Fixed issue #19 'Rake not auto completing'.  The stat command syntax that was being used was not correct. Or at least on my machine.  See man page for the stat command"
  * Added initial jnrowe theme.
  * Fixed issue #25.
  * Fixed darkblood theme as in issue #23.
  * Whoops, forgot to include this dummy precmd implementation.
  * Added my prompt theme, with a tweak to the core oh-my-zsh to support it. My git_prompt_info function not only reports the branch and dirty status, but also whether or not the branch is ahead or behind of the remote, or both. It also switches the prompt colour from green to red if the previous command exited with a non-zero value (i.e. failed).
  * parse error fix
  * Enabled colors in ls and made it possible to theme them
  * added LSCOLORS
  * Joined the appearance so the theme can apply LSCOLORS too
  * Merge branch 'master' of git://github.com/robbyrussell/oh-my-zsh
  * Adding devlog alias for tailing development.log for Rails
  * Skip the git word in this theme
  * Small fix, probably the smallest possible
  * Added my theme
  * Added darkblod theme.
  * Fixing some conflict residue that I missed in a commit/merge:
  * Merge branch 'master' of git://github.com/kastner/oh-my-zsh into kastner/master
  * Merge branch 'master' of git://github.com/mrinterweb/oh-my-zsh into mrinterweb/master
  * Fixing merge conflicts 886d97f41e72b8662232a2c6b196fb60508e4f67
  * lsa now uses coloring
  * ll doesn't show hidden files, lsa does
  * Merging conflict. 788c9af05684f4b9e39e7f15de2c06c4c8291cbd
  * Merge branch 'master' of git://github.com/mdonoughe/oh-my-zsh into mdonoughe/master
  * adding homebrew completions - and a function dir
  * Fixed issue #19 'Rake not auto completing'.  The stat command syntax that was being used was not correct. Or at least on my machine.  See man page for the stat command
  * Removed useless else
  * Fixing merge
  * extended path variable, temporary
  * Renaming script/server --debug alias to ssd to avoid conflict. Closes #1
  * added gcp alias (git cherry-pick)
  * Added some comment
  * Merge branch 'master' of git://github.com/wezm/oh-my-zsh into wezm/master
  * Merge branch 'cypher/master'
  * Added more aliases for Rails & git
  * Added ack-grep searching
  * Added git diff for vim (gdv)
  * Replaced source with .
  * Add my own theme
  * should probably use the value of CASE_INSENSITIVE
  * allow case sensitivity to be toggled
  * Fix cypher's theme for older zsh versions
  * Merge branch 'master' of git://github.com/cypher/oh-my-zsh into cypher/master
  * add xiong-chiamiov theme
  * Make "-" an alias for "cd -" (cd back to previous directory)
  * Add my (cypher's) zsh prompt
  * run update check *after* running custom configuration scripts. This means we are running it after $PATH has potentially been set up, which means it's more likely that commands like "git" will be found
  * Oh My Zsh gets a weekly auto-updater... the future is now!
  * Adding a script to check for upgrades
  * put everything in lib
  * merge upstream
  * Bumping up history to 10k commands
  * Updating README to mention custom/ directory
  * not ignoring example.zsh
  * Updating .gitignore to ignore everything but the example.zsh file in custom/
  * Moving some example files into custom/
  * Moving all zsh config options into a lib/ subdirectory to make way for some upcoming changes to directory structure and configuration options
  * Using compctl instead of compdef to resolve Issue #1
  * Merge remote branch 'upstream/master'
  * add in refcard note
  * more fixes, more or less have this as i want
  * further refactorings
  * misc useful
  * tidy up history
  * Added a new theme
  * would rather store history in $HOME and double size
  * some todo notes, take @chris2's titlebar improvements and poke at completions
  * minimalist
  * add in xterms / title hacks
  * Merge remote branch 'upstream/master'
  * Git 1.6 support
  * Improved git prompt handling
  * make correction work; this is a nicer way of handling typos in commands
  * some helpers to make directory traversal go easier....
  * Adding a little documentation for the git themes
  * Added risto theme and made git.zsh themable
  * Updating the name of the rake and capistrano task cache file to append a ~ to the end of the filename so it's easier to ignore in rails git projects. [#1]
  * Updating install process to copy your current environments PATH and adding it to the bottom of ~/.zshrc.
  * Merge branch 'master' of git://github.com/mwilliams/oh-my-zsh into mwilliams/master
  * added case-insensitive auto completion
  * Adding more useful aliases for Git.
  * Moving bindings into their own file. Updating aliases after moving out bindings
  * Trying out some zsh-fu. Using the for x (*.zsh) source  approach
  * Updating README to instruct people to copy the .zshrc template file versus symlinking it.
  * Updating installer to use the new template file. ~/.zshrc will now be outside of the repository
  * Updating the template file to use the oh-my-zsh.sh loader
  * Renaming template file one last time (for now)
  * Moving and renaming the zshrc file to a template file
  * Moving the loading of all .zsh files into a different file so that we can remove zshrc from the repository
  * Including a link to the Themes wiki page from the README
  * Added extra theme with full pathnames and hostname
  * Adding an upgrade_oh_my_zsh function to... well, upgrade Oh My Zsh
  * Removing left over theme reference to geoffs theme
  * Merging geoffgarside work
  * Adding an uninstaller tool
  * Adding zsh_stats function to show you which commands you run the most.
  * Move the spaces around again :P
  * Merge branch 'master' of git@github.com:geoffgarside/oh-my-zsh
  * Only calling git symbolic-ref HEAD when we are in a .git directory
  * Restructure spaces in git pieces
  * Switch double quotes for singles, fixes prompt issues
  * Add my own theme
  * Colour branch name and add dirty string
  * Change dirty git string to a yello X
  * Remove colour from ls command
  * Adding a file into log/ so that we have a log file to record history to
  * Remove PATH definition as we define this in .profile
  * Add geoffgarside theme
  * Merge branch master
  * Adding Evan's skinny, topless prompt.
  * Updating README with info about themes
  * Adding theme support so that people can share their zsh prompts with others. Users can set which theme to load in zshrc now.
  * Add tab, take and tm functions
  * Customise prompt value
  * Use my normal PATH instead of included
  * Strip colours from git.zsh
  * Swap out g alias to git
  * Add textmate aliases
  * Add in my normal s{s,d} aliases
  * Updating README to match new path for installation.
  * Changing order of loading zsh at end of install
  * Attempting to load zsh properly after auto-install
  * Checking if .zshrc is a file or a symlink.
  * Updating README with reference to auto-installer
  * Adding an installer tool
  * Adding a note about backing up your existing zshrc file
  * Updating README to show people how to change their default shell.
  * Removing some unused git-dirty parsing code.
  * Removed a bunch of aliases that I never use, which came from someone else I copied old config from
  * Removing a robby-only alias
  * Moving some more config into prompt.zsh to reduce amount of code in .zshrc
  * Info about contributing
  * Updating README regarding PATH info
  * Note about PATH
  * Making sure it's obvious to symlink to ~/.zshrc
  * Merge branch 'master' of git://github.com/eddorre/oh-my-zsh into eddorre/master
  * Adding some info to the Usage section of the README
  * Updating README
  * Loading all files in /Users/robbyrussell/oh-my-zsh that end in .zsh instead of specifying them manually
  * Removed Git Aliases comment since there are no Git aliases in this file
  * Updating README file
  * Changing path to oh-my-zsh in zshrc
  * Importing initial files after reorganizing stuff.
  * Adding initial gitignore file
