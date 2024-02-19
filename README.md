# espanso-wayland 2.2.1 for nixos 
espanso-wayland for nixos (tested on nixos + hyprland), based on package https://github.com/NixOS/nixpkgs/tree/nixos-unstable/pkgs/applications/office/espanso

1. Clone project: git clone https://github.com/ingbarrozo/espanso.git

2. Move ‘espanso’ folder to a desired path.

3. Import the module to your home-manager.
  example:
  imports = [
    ./espanso
  ]

4. Add your user to group input
   example:
   users.users."yourusername".extraGroups = [ "input" ];

5. espanso service register

6. espanso restart
