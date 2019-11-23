FROM brandonkal/brew:bionic

COPY Brewfile /home/linuxbrew/Brewfile
RUN brew bundle && echo '===Clean Up===' && brew cleanup

