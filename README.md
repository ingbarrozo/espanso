# espanso-wayland 2.2.1 for nixos 
espanso-wayland for nixos (tested on nixos + hyprland), based on package https://github.com/NixOS/nixpkgs/tree/nixos-unstable/pkgs/applications/office/espanso

1. Clone project: git clone https://github.com/ingbarrozo/espanso.git

2. Move ‘espanso’ folder to a desired path.

3. Import the module to your home-manager.

4. enable espanso 

  example:
    imports = [
      ./espanso
    ]
    programs.espanso.enable = true;

6. Add your user to group input
   example:
   users.users."yourusername".extraGroups = [ "input" ];

7. espanso service register

8. espanso restart
