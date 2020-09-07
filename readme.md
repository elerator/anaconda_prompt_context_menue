# Add open anaconda Promt here to context menu

see https://stackoverflow.com/questions/46662881/adding-open-anaconda-prompt-here-to-context-menu-windows

Run either setup_context_menu.bat or setup_context_menu_global_installation.bat as administrator. The earlier is suitable if you installed anaconda for the current user only (install location %%USERPROFILE%%\\Anaconda3) while the latter should work if you installed anaconda as the administrator for all users (install location C:\ProgramData\Anaconda3).

If you used another directory to install anaconda adjust the path accordingly.
