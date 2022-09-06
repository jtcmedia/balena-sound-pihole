# Combined Balena Sound and Pi-Hole Project Using Git Submodules

To Build and Deploy:

`balena login`

then:

`balena push pi4-balena-sound-and-pi-hole --registry-secrets .\secrets.yml

To update each project (git submodule), run:
`git submodule foreach git pull origin master`
