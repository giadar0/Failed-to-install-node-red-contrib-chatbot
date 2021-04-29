npm WARN deprecated node-pre-gyp@0.11.0: Please upgrade to @mapbox/node-pre-gyp: the non-scoped node-pre-gyp package is deprecated and only the @mapbox scoped package will recieve updates in the future
npm ERR! code 1
npm ERR! path C:\Users\Utente\node_modules\sqlite3
npm ERR! command failed
npm ERR! command C:\WINDOWS\system32\cmd.exe /d /s /c node-pre-gyp install --fallback-to-build
npm ERR! Failed to execute 'C:\Program Files\nodejs\node.exe C:\Users\Utente\AppData\Roaming\npm\node_modules\npm\node_modules\node-gyp\bin\node-gyp.js configure --fallback-to-build --module=C:\Users\Utente\node_modules\sqlite3\lib\binding\node-v93-win32-x64\node_sqlite3.node --module_name=node_sqlite3 --module_path=C:\Users\Utente\node_modules\sqlite3\lib\binding\node-v93-win32-x64 --napi_version=8 --node_abi_napi=napi --napi_build_version=0 --node_napi_label=node-v93' (1)
npm ERR! node-pre-gyp info it worked if it ends with ok
npm ERR! node-pre-gyp info using node-pre-gyp@0.11.0
npm ERR! node-pre-gyp info using node@16.0.0 | win32 | x64
npm ERR! node-pre-gyp WARN Using request for node-pre-gyp https download
npm ERR! node-pre-gyp info check checked for "C:\Users\Utente\node_modules\sqlite3\lib\binding\node-v93-win32-x64\node_sqlite3.node" (not found)
npm ERR! node-pre-gyp http GET https://mapbox-node-binary.s3.amazonaws.com/sqlite3/v4.2.0/node-v93-win32-x64.tar.gz
npm ERR! node-pre-gyp http 403 https://mapbox-node-binary.s3.amazonaws.com/sqlite3/v4.2.0/node-v93-win32-x64.tar.gz
npm ERR! node-pre-gyp WARN Tried to download(403): https://mapbox-node-binary.s3.amazonaws.com/sqlite3/v4.2.0/node-v93-win32-x64.tar.gz
npm ERR! node-pre-gyp WARN Pre-built binaries not found for sqlite3@4.2.0 and node@16.0.0 (node-v93 ABI, unknown) (falling back to source compile with node-gyp)
npm ERR! node-pre-gyp http 403 status code downloading tarball https://mapbox-node-binary.s3.amazonaws.com/sqlite3/v4.2.0/node-v93-win32-x64.tar.gz
npm ERR! gyp info it worked if it ends with ok
npm ERR! gyp info using node-gyp@7.1.2
npm ERR! gyp info using node@16.0.0 | win32 | x64
npm ERR! gyp info ok
npm ERR! gyp info it worked if it ends with ok
npm ERR! gyp info using node-gyp@7.1.2
npm ERR! gyp info using node@16.0.0 | win32 | x64
npm ERR! gyp ERR! find Python
npm ERR! gyp ERR! find Python Python is not set from command line or npm configuration
npm ERR! gyp ERR! find Python Python is not set from environment variable PYTHON
npm ERR! gyp ERR! find Python checking if "python3" can be used
npm ERR! gyp ERR! find Python - "python3" is not in PATH or produced an error
npm ERR! gyp ERR! find Python checking if "python" can be used
npm ERR! gyp ERR! find Python - "python" is not in PATH or produced an error
npm ERR! gyp ERR! find Python checking if "python2" can be used
npm ERR! gyp ERR! find Python - "python2" is not in PATH or produced an error
npm ERR! gyp ERR! find Python checking if Python is C:\Python37\python.exe
npm ERR! gyp ERR! find Python - "C:\Python37\python.exe" could not be run
npm ERR! gyp ERR! find Python checking if Python is C:\Python27\python.exe
npm ERR! gyp ERR! find Python - "C:\Python27\python.exe" could not be run
npm ERR! gyp ERR! find Python checking if the py launcher can be used to find Python
npm ERR! gyp ERR! find Python - "py.exe" is not in PATH or produced an error
npm ERR! gyp ERR! find Python
npm ERR! gyp ERR! find Python **********************************************************
npm ERR! gyp ERR! find Python You need to install the latest version of Python.
npm ERR! gyp ERR! find Python Node-gyp should be able to find and use Python. If not,
npm ERR! gyp ERR! find Python you can try one of the following options:
npm ERR! gyp ERR! find Python - Use the switch --python="C:\Path\To\python.exe"
npm ERR! gyp ERR! find Python   (accepted by both node-gyp and npm)
npm ERR! gyp ERR! find Python - Set the environment variable PYTHON
npm ERR! gyp ERR! find Python - Set the npm configuration variable python:
npm ERR! gyp ERR! find Python   npm config set python "C:\Path\To\python.exe"
npm ERR! gyp ERR! find Python For more information consult the documentation at:
npm ERR! gyp ERR! find Python https://github.com/nodejs/node-gyp#installation
npm ERR! gyp ERR! find Python **********************************************************
npm ERR! gyp ERR! find Python
npm ERR! gyp ERR! configure error
npm ERR! gyp ERR! stack Error: Could not find any Python installation to use
npm ERR! gyp ERR! stack     at PythonFinder.fail (C:\Users\Utente\AppData\Roaming\npm\node_modules\npm\node_modules\node-gyp\lib\find-python.js:302:47)
npm ERR! gyp ERR! stack     at PythonFinder.runChecks (C:\Users\Utente\AppData\Roaming\npm\node_modules\npm\node_modules\node-gyp\lib\find-python.js:136:21)
npm ERR! gyp ERR! stack     at PythonFinder.<anonymous> (C:\Users\Utente\AppData\Roaming\npm\node_modules\npm\node_modules\node-gyp\lib\find-python.js:200:18)
npm ERR! gyp ERR! stack     at PythonFinder.execFileCallback (C:\Users\Utente\AppData\Roaming\npm\node_modules\npm\node_modules\node-gyp\lib\find-python.js:266:16)
npm ERR! gyp ERR! stack     at exithandler (node:child_process:333:5)
npm ERR! gyp ERR! stack     at ChildProcess.errorhandler (node:child_process:345:5)
npm ERR! gyp ERR! stack     at ChildProcess.emit (node:events:365:28)
npm ERR! gyp ERR! stack     at Process.ChildProcess._handle.onexit (node:internal/child_process:288:12)
npm ERR! gyp ERR! stack     at onErrorNT (node:internal/child_process:480:16)
npm ERR! gyp ERR! stack     at processTicksAndRejections (node:internal/process/task_queues:83:21)
npm ERR! gyp ERR! System Windows_NT 10.0.19042
npm ERR! gyp ERR! command "C:\\Program Files\\nodejs\\node.exe" "C:\\Users\\Utente\\AppData\\Roaming\\npm\\node_modules\\npm\\node_modules\\node-gyp\\bin\\node-gyp.js" "configure" "--fallback-to-build" "--module=C:\\Users\\Utente\\node_modules\\sqlite3\\lib\\binding\\node-v93-win32-x64\\node_sqlite3.node" "--module_name=node_sqlite3" "--module_path=C:\\Users\\Utente\\node_modules\\sqlite3\\lib\\binding\\node-v93-win32-x64" "--napi_version=8" "--node_abi_napi=napi" "--napi_build_version=0" "--node_napi_label=node-v93"
npm ERR! gyp ERR! cwd C:\Users\Utente\node_modules\sqlite3
npm ERR! gyp ERR! node -v v16.0.0
npm ERR! gyp ERR! node-gyp -v v7.1.2
npm ERR! gyp ERR! not ok
npm ERR! node-pre-gyp ERR! build error
npm ERR! node-pre-gyp ERR! stack Error: Failed to execute 'C:\Program Files\nodejs\node.exe C:\Users\Utente\AppData\Roaming\npm\node_modules\npm\node_modules\node-gyp\bin\node-gyp.js configure --fallback-to-build --module=C:\Users\Utente\node_modules\sqlite3\lib\binding\node-v93-win32-x64\node_sqlite3.node --module_name=node_sqlite3 --module_path=C:\Users\Utente\node_modules\sqlite3\lib\binding\node-v93-win32-x64 --napi_version=8 --node_abi_napi=napi --napi_build_version=0 --node_napi_label=node-v93' (1)
npm ERR! node-pre-gyp ERR! stack     at ChildProcess.<anonymous> (C:\Users\Utente\node_modules\node-pre-gyp\lib\util\compile.js:83:29)
npm ERR! node-pre-gyp ERR! stack     at ChildProcess.emit (node:events:365:28)
npm ERR! node-pre-gyp ERR! stack     at maybeClose (node:internal/child_process:1067:16)
npm ERR! node-pre-gyp ERR! stack     at Process.ChildProcess._handle.onexit (node:internal/child_process:301:5)
npm ERR! node-pre-gyp ERR! System Windows_NT 10.0.19042
npm ERR! node-pre-gyp ERR! command "C:\\Program Files\\nodejs\\node.exe" "C:\\Users\\Utente\\node_modules\\node-pre-gyp\\bin\\node-pre-gyp" "install" "--fallback-to-build"
npm ERR! node-pre-gyp ERR! cwd C:\Users\Utente\node_modules\sqlite3
npm ERR! node-pre-gyp ERR! node -v v16.0.0
npm ERR! node-pre-gyp ERR! node-pre-gyp -v v0.11.0
npm ERR! node-pre-gyp ERR! not ok

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Utente\AppData\Local\npm-cache\_logs\2021-04-29T19_13_08_031Z-debug.log
