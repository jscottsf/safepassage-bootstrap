# Safe Passage Bootstrap

Defines variables and build scripts for a custom build of Bootstrap 4.1.x.


# Instructions

1. Download and extract the Bootstrap source files to a separate directory, such as `bootstrap-4.1.1`. This should be outside of this repo’s project directory.

2. Complete the Bootstrap [Tooling setup](https://getbootstrap.com/docs/4.1/getting-started/build-tools/#tooling-setup) instructions.

3. Make this project directory the current directory, i.e. `cd safepassage-bootstrap`.

4. Feel free to modify variables in `scss/_override.variables.scss` to customize the build. Be sure to commit any changes.

5. To perform the build, specify the location of the external Bootstrap source files and run the build script as shown:

	```bash
	$ BOOTSTRAP=../bootstrap npm run build
	```

6. If all goes well, the compiled Bootstrap files will be copied to this project’s `dist` directory.
