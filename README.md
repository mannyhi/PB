(venv) C:\Users\Z318291\Desktop\test>pip install pandas==1.4.1
Collecting pandas==1.4.1
  Using cached https://files.pythonhosted.org/packages/c4/eb/cfa96ba42695b3c28d4864a796d492f188471dd536df7e5e5e0c54b629a6/pandas-1.4.1.tar.gz
  Installing build dependencies ... error
  Complete output from command C:\Users\Z318291\Desktop\test\venv\Scripts\python.exe C:\Users\Z318291\Desktop\test\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip install --ignore-installed --no-user --prefix C
:\Users\Z318291\AppData\Local\Temp\pip-build-env-mzmambxl\overlay --no-warn-script-location --no-binary :none: --only-binary :none: -i https://pypi.org/simple -- setuptools>=51.0.0 wheel Cython>=0.29.24,<3 olde
st-supported-numpy>=0.10:
  Collecting setuptools>=51.0.0
    Downloading https://files.pythonhosted.org/packages/c3/9e/8a7ba2c9984a060daa6c6f9fff4d576b7ace3936239d6b771541eab972ed/setuptools-67.6.0-py3-none-any.whl (1.1MB)
  Collecting wheel
    Using cached https://files.pythonhosted.org/packages/bd/7c/d38a0b30ce22fc26ed7dbc087c6d00851fb3395e9d0dac40bec1f905030c/wheel-0.38.4-py3-none-any.whl
  Collecting Cython<3,>=0.29.24
    Using cached https://files.pythonhosted.org/packages/56/3a/e59db3769dee48409c759a88b62cd605324e05d396e10af0a065adc956ad/Cython-0.29.33-py2.py3-none-any.whl
  Collecting oldest-supported-numpy>=0.10
    Using cached https://files.pythonhosted.org/packages/2e/43/38818233e4bfea43f6ce9bebef9f5533d098fbf009e7a3a1d52a25613367/oldest_supported_numpy-2022.11.19-py3-none-any.whl
  Collecting numpy==1.17.3; python_version == "3.8" and platform_machine not in "arm64|aarch64|s390x|loongarch64" and platform_python_implementation != "PyPy" (from oldest-supported-numpy>=0.10)
    Using cached https://files.pythonhosted.org/packages/b6/d6/be8f975f5322336f62371c9abeb936d592c98c047ad63035f1b38ae08efe/numpy-1.17.3.zip
  Installing collected packages: setuptools, wheel, Cython, numpy, oldest-supported-numpy
    Running setup.py install for numpy: started
      Running setup.py install for numpy: finished with status 'error'
      Complete output from command C:\Users\Z318291\Desktop\test\venv\Scripts\python.exe -u -c "import setuptools, tokenize;__file__='C:\\Users\\Z318291\\AppData\\Local\\Temp\\pip-install-zlnnezg6\\numpy\\setup
.py';f=getattr(tokenize, 'open', open)(__file__);code=f.read().replace('\r\n', '\n');f.close();exec(compile(code, __file__, 'exec'))" install --record C:\Users\Z318291\AppData\Local\Temp\pip-record-dnlmq28a\ins
tall-record.txt --single-version-externally-managed --prefix C:\Users\Z318291\AppData\Local\Temp\pip-build-env-mzmambxl\overlay --compile --install-headers C:\Users\Z318291\Desktop\test\venv\include\site\python
3.8\numpy:
      Running from numpy source directory.

      Note: if you need reliable uninstall behavior, then install
      with pip instead of using `setup.py install`:

        - `pip install .`       (from a git repo or downloaded source
                                 release)
        - `pip install numpy`   (last NumPy release on PyPi)


      blas_opt_info:
      blas_mkl_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries mkl_rt not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      blis_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries blis not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      openblas_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries openblas not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
      get_default_fcompiler: matching types: '['gnu', 'intelv', 'absoft', 'compaqv', 'intelev', 'gnu95', 'g95', 'intelvem', 'intelem', 'flang']'
      customize GnuFCompiler
      Could not locate executable g77
      Could not locate executable f77
      customize IntelVisualFCompiler
      Could not locate executable ifort
      Could not locate executable ifl
      customize AbsoftFCompiler
      Could not locate executable f90
      customize CompaqVisualFCompiler
      Could not locate executable DF
      customize IntelItaniumVisualFCompiler
      Could not locate executable efl
      customize Gnu95FCompiler
      Could not locate executable gfortran
      Could not locate executable f95
      customize G95FCompiler
      Could not locate executable g95
      customize IntelEM64VisualFCompiler
      customize IntelEM64TFCompiler
      Could not locate executable efort
      Could not locate executable efc
      customize PGroupFlangCompiler
      Could not locate executable flang
      don't know how to compile Fortran code on platform 'nt'
        NOT AVAILABLE

      atlas_3_10_blas_threads_info:
      Setting PTATLAS=ATLAS
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries tatlas not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      atlas_3_10_blas_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries satlas not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      atlas_blas_threads_info:
      Setting PTATLAS=ATLAS
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries ptf77blas,ptcblas,atlas not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      atlas_blas_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries f77blas,cblas,atlas not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      accelerate_info:
        NOT AVAILABLE

      C:\Users\Z318291\AppData\Local\Temp\pip-install-zlnnezg6\numpy\numpy\distutils\system_info.py:690: UserWarning:
          Optimized (vendor) Blas libraries are not found.
          Falls back to netlib Blas library which has worse performance.
          A better performance should be easily gained by switching
          Blas library.
        self.calc_info()
      blas_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries blas not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      C:\Users\Z318291\AppData\Local\Temp\pip-install-zlnnezg6\numpy\numpy\distutils\system_info.py:690: UserWarning:
          Blas (http://www.netlib.org/blas/) libraries not found.
          Directories to search for the libraries can be specified in the
          numpy/distutils/site.cfg file (section [blas]) or by setting
          the BLAS environment variable.
        self.calc_info()
      blas_src_info:
        NOT AVAILABLE

      C:\Users\Z318291\AppData\Local\Temp\pip-install-zlnnezg6\numpy\numpy\distutils\system_info.py:690: UserWarning:
          Blas (http://www.netlib.org/blas/) sources not found.
          Directories to search for the sources can be specified in the
          numpy/distutils/site.cfg file (section [blas_src]) or by setting
          the BLAS_SRC environment variable.
        self.calc_info()
        NOT AVAILABLE

      'svnversion' is not recognized as an internal or external command,
      operable program or batch file.
      non-existing path in 'numpy\\distutils': 'site.cfg'
      lapack_opt_info:
      lapack_mkl_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries mkl_rt not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      openblas_lapack_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries openblas not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      openblas_clapack_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries openblas,lapack not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      flame_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries flame not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      atlas_3_10_threads_info:
      Setting PTATLAS=ATLAS
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries lapack_atlas not found in C:\Users\Z318291\Desktop\test\venv\lib
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries tatlas,tatlas not found in C:\Users\Z318291\Desktop\test\venv\lib
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries lapack_atlas not found in C:\
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries tatlas,tatlas not found in C:\
      <class 'numpy.distutils.system_info.atlas_3_10_threads_info'>
        NOT AVAILABLE

      atlas_3_10_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries lapack_atlas not found in C:\Users\Z318291\Desktop\test\venv\lib
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries satlas,satlas not found in C:\Users\Z318291\Desktop\test\venv\lib
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries lapack_atlas not found in C:\
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries satlas,satlas not found in C:\
      <class 'numpy.distutils.system_info.atlas_3_10_info'>
        NOT AVAILABLE

      atlas_threads_info:
      Setting PTATLAS=ATLAS
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries lapack_atlas not found in C:\Users\Z318291\Desktop\test\venv\lib
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries ptf77blas,ptcblas,atlas not found in C:\Users\Z318291\Desktop\test\venv\lib
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries lapack_atlas not found in C:\
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries ptf77blas,ptcblas,atlas not found in C:\
      <class 'numpy.distutils.system_info.atlas_threads_info'>
        NOT AVAILABLE

      atlas_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries lapack_atlas not found in C:\Users\Z318291\Desktop\test\venv\lib
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries f77blas,cblas,atlas not found in C:\Users\Z318291\Desktop\test\venv\lib
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries lapack_atlas not found in C:\
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries f77blas,cblas,atlas not found in C:\
      <class 'numpy.distutils.system_info.atlas_info'>
        NOT AVAILABLE

      lapack_info:
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      customize MSVCCompiler
        libraries lapack not found in ['C:\\Users\\Z318291\\Desktop\\test\\venv\\lib', 'C:\\']
        NOT AVAILABLE

      C:\Users\Z318291\AppData\Local\Temp\pip-install-zlnnezg6\numpy\numpy\distutils\system_info.py:1712: UserWarning:
          Lapack (http://www.netlib.org/lapack/) libraries not found.
          Directories to search for the libraries can be specified in the
          numpy/distutils/site.cfg file (section [lapack]) or by setting
          the LAPACK environment variable.
        if getattr(self, '_calc_info_{}'.format(lapack))():
      lapack_src_info:
        NOT AVAILABLE

      C:\Users\Z318291\AppData\Local\Temp\pip-install-zlnnezg6\numpy\numpy\distutils\system_info.py:1712: UserWarning:
          Lapack (http://www.netlib.org/lapack/) sources not found.
          Directories to search for the sources can be specified in the
          numpy/distutils/site.cfg file (section [lapack_src]) or by setting
          the LAPACK_SRC environment variable.
        if getattr(self, '_calc_info_{}'.format(lapack))():
        NOT AVAILABLE

      C:\Program Files\Python38\lib\distutils\dist.py:274: UserWarning: Unknown distribution option: 'define_macros'
        warnings.warn(msg)
      running install
      running build
      running config_cc
      unifing config_cc, config, build_clib, build_ext, build commands --compiler options
      running config_fc
      unifing config_fc, config, build_clib, build_ext, build commands --fcompiler options
      running build_src
      build_src
      building py_modules sources
      creating build
      creating build\src.win-amd64-3.8
      creating build\src.win-amd64-3.8\numpy
      creating build\src.win-amd64-3.8\numpy\distutils
      building library "npymath" sources
      No module named 'numpy.distutils._msvccompiler' in numpy.distutils; trying from distutils
      error: Microsoft Visual C++ 14.0 is required. Get it with "Microsoft Visual C++ Build Tools": https://visualstudio.microsoft.com/downloads/

      ----------------------------------------
  Command "C:\Users\Z318291\Desktop\test\venv\Scripts\python.exe -u -c "import setuptools, tokenize;__file__='C:\\Users\\Z318291\\AppData\\Local\\Temp\\pip-install-zlnnezg6\\numpy\\setup.py';f=getattr(tokenize,
 'open', open)(__file__);code=f.read().replace('\r\n', '\n');f.close();exec(compile(code, __file__, 'exec'))" install --record C:\Users\Z318291\AppData\Local\Temp\pip-record-dnlmq28a\install-record.txt --single
-version-externally-managed --prefix C:\Users\Z318291\AppData\Local\Temp\pip-build-env-mzmambxl\overlay --compile --install-headers C:\Users\Z318291\Desktop\test\venv\include\site\python3.8\numpy" failed with e
rror code 1 in C:\Users\Z318291\AppData\Local\Temp\pip-install-zlnnezg6\numpy\

  ----------------------------------------
Command "C:\Users\Z318291\Desktop\test\venv\Scripts\python.exe C:\Users\Z318291\Desktop\test\venv\lib\site-packages\pip-19.0.3-py3.8.egg\pip install --ignore-installed --no-user --prefix C:\Users\Z318291\AppDat
a\Local\Temp\pip-build-env-mzmambxl\overlay --no-warn-script-location --no-binary :none: --only-binary :none: -i https://pypi.org/simple -- setuptools>=51.0.0 wheel Cython>=0.29.24,<3 oldest-supported-numpy>=0.
10" failed with error code 1 in None
