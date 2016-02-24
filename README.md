Setting up BattleSchool 
===========

1. Install pip: `sudo easy_install pip`
2. FIX FOR battleschool 0.8.0 is to preinstall ansible 1.9.4 (ansible >= 2.0)
  `sudo pip install ansible==1.9.4`
3. Install battleschool: `sudo pip install battleschool`
4. Create alias in the .profile:
  `alias battle='battle --ask-sudo-pass --config-file https://raw.githubusercontent.com/vadimich/ansible-osx/master/config.yml'`
5. Run: `battle`
