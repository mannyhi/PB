pip --version
> pip 7.1.2 from c:\program files\python35\lib\site-packages (python 3.5)

pip install requirements.txt
> Collecting requirements.txt
  Could not find a version that satisfies the requirement requirements.txt (from versions: )
No matching distribution found for requirements.txt
You are using pip version 7.1.2, however version 23.0.1 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.

python -m pip install --upgrade pip
> Collecting pip
  Using cached https://files.pythonhosted.org/packages/07/51/2c0959c5adf988c44d9e1e0d940f5b074516ecc87e96b1af25f59de9ba38/pip-23.0.1-py3-none-any.whl
Installing collected packages: pip
  Found existing installation: pip 7.1.2
    Uninstalling pip-7.1.2:
Exception:
Traceback (most recent call last):
  File "C:\Program Files\Python35\lib\shutil.py", line 538, in move
    os.rename(src, real_dst)
PermissionError: [WinError 5] Access is denied: 'c:\\program files\\python35\\lib\\site-packages\\pip-7.1.2.dist-info\\description.rst' -> 'C:\\Users\\Z318291\\
AppData\\Local\\Temp\\pip-1tgp63ch-uninstall\\program files\\python35\\lib\\site-packages\\pip-7.1.2.dist-info\\description.rst'

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "C:\Program Files\Python35\lib\site-packages\pip\basecommand.py", line 211, in main
    status = self.run(options, args)
  File "C:\Program Files\Python35\lib\site-packages\pip\commands\install.py", line 311, in run
    root=options.root_path,
  File "C:\Program Files\Python35\lib\site-packages\pip\req\req_set.py", line 640, in install
    requirement.uninstall(auto_confirm=True)
  File "C:\Program Files\Python35\lib\site-packages\pip\req\req_install.py", line 716, in uninstall
    paths_to_remove.remove(auto_confirm)
  File "C:\Program Files\Python35\lib\site-packages\pip\req\req_uninstall.py", line 125, in remove
    renames(path, new_path)
  File "C:\Program Files\Python35\lib\site-packages\pip\utils\__init__.py", line 315, in renames
    shutil.move(old, new)
  File "C:\Program Files\Python35\lib\shutil.py", line 553, in move
    os.unlink(src)
PermissionError: [WinError 5] Access is denied: 'c:\\program files\\python35\\lib\\site-packages\\pip-7.1.2.dist-info\\description.rst'
You are using pip version 7.1.2, however version 23.0.1 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.

pip install -r requirements.txt
Collecting confluent-kafka==1.9.2 (from -r requirements.txt (line 1))
  Using cached https://files.pythonhosted.org/packages/4d/97/2d9c7c0bb5c925bd5abef670ffd78c77f239804dcaa89fa101314d43e03f/confluent-kafka-1.9.2.tar.gz
    Complete output from command python setup.py egg_info:
    error in confluent-kafka setup command: 'install_requires' must be a string or list of strings containing valid project/version requirement specifiers; Expe
cted version spec in futures;python_version<"3.2" at ;python_version<"3.2"

    ----------------------------------------
Command "python setup.py egg_info" failed with error code 1 in C:\Users\Z318291\AppData\Local\Temp\pip-build-th6vdiwg\confluent-kafka

