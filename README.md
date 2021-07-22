# Jesse-R-Studio-GitHub
Jesse's linked R-Studio-GitHub Repository

Jesse's linked R-Studio-GitHub Repository notes:

7/21/21: Git for R-Studio link: https://github.com/
acct for jesse.gordon@ranchobiosciences.com with Ron!20 password username JesseGordonRancho
RESULT OF GIT-HUB IS: https://github.com/JesseGordonRancho
To use with R-Studio: Downloaded GIT from "Git-Scam" sie as recommended: https://git-scm.com/downloads

Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. 
You do not need GitHub to use git, but you cannot use GitHub without using git.
Git Bash is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience. Bash is an acronym for Bourne Again Shell. 
(Amber expected me to figure this al lout on my own? Plus R-Studio link? No way!) Gotta do this in Bash:
git config --global user.email jesse.gordon@ranchobiosciences.com 
git config --global user.name "Jesse Gordon"
git config --list       === to confirm changes
Jesse note: The Coursera user guide is below – then the GitHub Guide from GitHub, which Coursera references and requires running through. Then comes how to link GitHub and R-Studio….. (there is a section on this in GNE "Rancho Onboarding" specific to Rosalind!)
> Tools > Global Options > Git/SVN > Git executable > C:/Program Files/Git/bin/git.exe
	> SVN executable > ~/R/my_first_R_script.R
	> SSH RSA key: > View public key…
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQC/FcH6etOQ/lyAa1t38Ak7YAtQFRZLlyuRFT6XeqyieFAtALOzJ0Er9OjMMDGAm0G3USYmZ4fw8/nhvNonNHc5k6kj8qMZrHsiYAccOSg3U/SXsQ2boRA4U+CiHvFgecQew/OgcflQayo9Yl3V+fxT8oVT2XWVf2RACOlKTMdh51AbuIfeSGnIAvdHTk4E+gRE51MQWufzetv9t0OZqpP7DnGogVSC3C3qbNuQib8/efve+6PMXPZjcLgudHIjjE3CnLZ4yjt3kheN2hST9RFXgb1W9EV8iarcLdvOIVz6B/ah4TnFWAXJY4KVjQqdbJarx2ehZjyg7KE1RTmjvD+Z11GnmGB5JCMiXCZAOCS8fVxLgELo6Bt8oBL9Tg0gi7CEnoAI9lkOYbmERUbHEkRJZ009dy7suBmrLEyD9LqfmZcvmuVUXoQOtcbf3GopSArTrVQdg0eeUK31lueKZPLI0QUC9XWrOsHfXEFmycFqgAWSvNSFzkIaqszi2gCI6y8= azuread\jessegordon@LT34-JGORDON

	> SSH RSA key: > Create RSA Key… > My passphrase is "his name" (just name capitalized)
Generating public/private rsa key pair.
Your identification has been saved in C:/Users/JesseGordon/.ssh/id_rsa.
Your public key has been saved in C:/Users/JesseGordon/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:PGFscoiLoFkntWwj/RDuDxCgiAKjR9b5j8V+ykKIMvE azuread\jessegordon@LT34-JGORDON
The key's randomart image is:
+---[RSA 3072]----+
|+.+.o.           |
|*+ *o+ o         |
|B * @.o.*        |
|+= O =.*o.       |
|oo..+..=S        |
|o E .oo o..      |
| o   ... o       |
|      . o        |
|       .         |
+----[SHA256]-----+
SSH RSA Key now says === C:/Users/JesseGordon/.ssh/id_rsa. Apply then restart R-Studio. 
Now go to GitHub and log in > Avatar > Settings > SSH an GPG keys > New SSH key > Title = "Jesse public key" > Key = [paste ssh-rsa from above]
Jesse public key   SHA256:PGFscoiLoFkntWwj/RDuDxCgiAKjR9b5j8V+ykKIMvE    Added on Jul 22, 2021Never used — Read/write
Now go to GitHub and create a new repository
