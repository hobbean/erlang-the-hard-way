Erlang The Hard Way OR Setting Up Ejabberd on a fresh EC2 Ubuntu Instance
=========================================================================

Just my notes on learning erlang and emacs. Man I lost a lot of notes in a chrome crash... the short version is I used brew, and git for a few things and ended up with emacs and evil going with a .emacs setup with distel... emacs seems really foreign for now... I'm switching over to getting ejabberd up and running.

sudo apt-get update
sudo apt-get install language-pack-en git build-essential autoconf

git clone git://github.com/sstephenson/rbenv.git ~/.rbenv
echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
exec $SHELL
git clone git://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
rbenv rehash
