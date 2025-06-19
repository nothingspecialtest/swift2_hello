curl -O https://download.swift.org/swiftly/linux/swiftly-$(uname -m).tar.gz && \
tar zxf swiftly-$(uname -m).tar.gz && \
./swiftly init --quiet-shell-followup && \
. "${SWIFTLY_HOME_DIR:-$HOME/.local/share/swiftly}/env.sh" && \
hash -r

Initialize a New Swift Package:
swift package init --type executable
This command sets up a new Swift package with a basic directory structure. Sources directory where your Swift files reside. Tests directory for any unit tests.

Build and Run Your Swift Package:
swift run

swift repl
:q


