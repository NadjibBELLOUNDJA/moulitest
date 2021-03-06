This repository contains tests of several projects done at 42.

# Install
1. Clone this repository wherever you want.
2. Make a **copy** of the "config.template" file and name it "config" (Do not delete "config.template")
3. Replace the "config" project paths with your own.

"config" file example
---------------------

	LIBFT_PATH = ~/path_to_my_libft_folder
	PROJECT2 = ~/path_to_my_project2_folder

As new tests will be available, there will be new variables in this example and you will have to update your config file with path of your new projects.

Usage
-----
To launch a test use inside this repository:

	$ make -C libft test # Example with libft.

Check Makefile of each project test to discover other commands.

# Credit

Those tests are mainly based on the work done by Maxime Bacoux "mbacoux" / "Nax" and

- Marc Pastor-Abad "mpastor-", intensive segfault testing.
- Sebastien Puyet "spuyet", pointless testing.
- François Montaro "fmontaro", close collaboration.
- Sebastien Sayada "ssayada", best debug failures ever.
- Nino Wextret "nwextret", intensive shower testing.
