# Puppet TextMate Bundle

This is a TextMate (http://www.macromates.com/) bundle for 
Puppet (http://www.reductivelabs.com/) manifests.

To install, clone this repository and drag the Puppet.tmbundle directory
on the TextMate icon. The installation will then be automatic.

This bundle supports directly:

   * syntax highlighting of most of the puppet syntax
   * common resources or standard language snippets
   * command to check syntax of manifests (puppet --parseonly)
   * function menu containing hierarchical class/nodes/define and resources titles
   * validates puppet on save with puppet-lint (1)
   * validates all puppet in projeto with ctrl+option+v (1)

To use last two features you need to have puppet-lint on command-line. To install it, typing on terminal:

    sudo gem install puppet-lint puppet
