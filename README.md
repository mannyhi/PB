(venv) C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation>pip install pandas==1.4.1

  ----------------------------------------
Command "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\Scripts\python.exe C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip insta
ll --ignore-installed --no-user --prefix C:\Users\Z318291\AppData\Local\Temp\pip-build-env-xf045f5i\overlay --no-warn-script-location --no-binary :none: --only-binary :none: -i https://pypi.org/simple -- setupt
ools>=51.0.0 wheel Cython>=0.29.24,<3 oldest-supported-numpy>=0.10" failed with error code 1 in None



(venv) C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation>pip install --upgrade pip


Exception:
Traceback (most recent call last):
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_internal\cli\base_command.py", line 179, in main
    status = self.run(options, args)
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_internal\commands\install.py", line 384, in run
    installed = install_given_reqs(
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_internal\req\__init__.py", line 53, in install_given_reqs
    requirement.install(
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_internal\req\req_install.py", line 910, in install
    self.move_wheel_files(
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_internal\req\req_install.py", line 437, in move_wheel_files
    move_wheel_files(
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_internal\wheel.py", line 544, in move_wheel_files
    generated.extend(maker.make(spec))
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_vendor\distlib\scripts.py", line 405, in make
    self._make_script(entry, filenames, options=options)
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_vendor\distlib\scripts.py", line 309, in _make_script
    self._write_script(scriptnames, shebang, script, filenames, ext)
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_vendor\distlib\scripts.py", line 245, in _write_script
    launcher = self._get_launcher('t')
  File "C:\Users\Z318291\PycharmProjects\NBS_Test_Platform_Automation\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip\_vendor\distlib\scripts.py", line 384, in _get_launcher
    result = finder(distlib_package).find(name).bytes
AttributeError: 'NoneType' object has no attribute 'bytes'
