# Official Repositoy of BengalBoot
## How to use on Other Arch Based OS:- 
Edit your pacman.conf using your favourite text editor. I have used sublime and my command was 

                                    sudo subl /etc/pacman.conf


 Add this to you pacman.conf file:-
                                      
                                      [bengal_repo]
                                      SigLevel = Optional TrustAll
                                      Server = https://bcw52.github.io/bengal_repo/$arch

                                                      

