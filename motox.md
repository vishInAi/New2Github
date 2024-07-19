[  1%] Built target glad
[  3%] Built target libccd
[  7%] Built target chipmunk
[ 16%] Built target lua
[ 17%] Built target md5sum
[ 37%] Built target ode
[ 38%] Built target xdgbasedir
[ 38%] Linking CXX executable xmoto
/usr/bin/ld: CMakeFiles/xmoto.dir/common/VTexture.cpp.o: in function `TextureManager::createTexture(std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, unsigned char*, int, int, bool, bool, FilterMode)':
VTexture.cpp:(.text+0x53f): undefined reference to `gluScaleImage'
/usr/bin/ld: VTexture.cpp:(.text+0x5f0): undefined reference to `gluBuild2DMipmaps'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::openIfNot(std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&)':
xmDatabase.cpp:(.text+0x1e7): undefined reference to `sqlite3_open'
/usr/bin/ld: xmDatabase.cpp:(.text+0x214): undefined reference to `sqlite3_errmsg'
/usr/bin/ld: xmDatabase.cpp:(.text+0x2ba): undefined reference to `sqlite3_busy_timeout'
/usr/bin/ld: xmDatabase.cpp:(.text+0x2d7): undefined reference to `sqlite3_trace'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::init(std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, bool, XmDatabaseUpdateInterface*)':
xmDatabase.cpp:(.text+0xffb): undefined reference to `sqlite3_close'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::~xmDatabase()':
xmDatabase.cpp:(.text+0x1edd): undefined reference to `sqlite3_close'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::getMemoryUsed()':
xmDatabase.cpp:(.text+0x2a25): undefined reference to `sqlite3_memory_used'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::getXmDbVersion()':
xmDatabase.cpp:(.text+0x2b96): undefined reference to `sqlite3_get_table'
/usr/bin/ld: xmDatabase.cpp:(.text+0x2bc7): undefined reference to `sqlite3_free'
/usr/bin/ld: xmDatabase.cpp:(.text+0x2c33): undefined reference to `sqlite3_free_table'
/usr/bin/ld: xmDatabase.cpp:(.text+0x2cad): undefined reference to `sqlite3_free_table'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::checkKey(std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&)':
xmDatabase.cpp:(.text+0x9102): undefined reference to `sqlite3_get_table'
/usr/bin/ld: xmDatabase.cpp:(.text+0x912a): undefined reference to `sqlite3_free'
/usr/bin/ld: xmDatabase.cpp:(.text+0x919b): undefined reference to `sqlite3_free_table'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::simpleSql(std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&)':
xmDatabase.cpp:(.text+0x9245): undefined reference to `sqlite3_exec'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9271): undefined reference to `sqlite3_free'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::readDB(std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, unsigned int&)':
xmDatabase.cpp:(.text+0x944b): undefined reference to `sqlite3_get_table'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9477): undefined reference to `sqlite3_free'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::read_DB_free(char**)':
xmDatabase.cpp:(.text+0x9608): undefined reference to `sqlite3_free_table'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::createUserFunctions()':
xmDatabase.cpp:(.text+0x9714): undefined reference to `sqlite3_create_function'
/usr/bin/ld: xmDatabase.cpp:(.text+0x977c): undefined reference to `sqlite3_create_function'
/usr/bin/ld: xmDatabase.cpp:(.text+0x97e4): undefined reference to `sqlite3_create_function'
/usr/bin/ld: xmDatabase.cpp:(.text+0x984c): undefined reference to `sqlite3_create_function'
/usr/bin/ld: xmDatabase.cpp:(.text+0x98b4): undefined reference to `sqlite3_create_function'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o:xmDatabase.cpp:(.text+0x991c): more undefined references to `sqlite3_create_function' follow
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::user_xm_floord(sqlite3_context*, int, sqlite3_value**)':
xmDatabase.cpp:(.text+0x9abd): undefined reference to `sqlite3_value_double'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9aed): undefined reference to `sqlite3_result_double'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::user_xm_lvlUpdatedToTxt(sqlite3_context*, int, sqlite3_value**)':
xmDatabase.cpp:(.text+0x9b65): undefined reference to `sqlite3_value_int'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9b9c): undefined reference to `sqlite3_result_text'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::user_xm_userCrappy(sqlite3_context*, int, sqlite3_value**)':
xmDatabase.cpp:(.text+0x9c15): undefined reference to `sqlite3_value_int'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9c41): undefined reference to `sqlite3_result_int'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::user_xm_userChildrenCompliant(sqlite3_context*, int, sqlite3_value**)':
xmDatabase.cpp:(.text+0x9cb9): undefined reference to `sqlite3_value_int'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9ce5): undefined reference to `sqlite3_result_int'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::user_xm_replaceStart(sqlite3_context*, int, sqlite3_value**)':
xmDatabase.cpp:(.text+0x9dc9): undefined reference to `sqlite3_value_text'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9df4): undefined reference to `sqlite3_value_text'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9e1f): undefined reference to `sqlite3_value_text'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9ecd): undefined reference to `sqlite3_result_text'
/usr/bin/ld: xmDatabase.cpp:(.text+0x9fb1): undefined reference to `sqlite3_result_text'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::user_xm_profile(sqlite3_context*, int, sqlite3_value**)':
xmDatabase.cpp:(.text+0xa196): undefined reference to `sqlite3_result_text'
/usr/bin/ld: CMakeFiles/xmoto.dir/db/xmDatabase.cpp.o: in function `xmDatabase::user_xm_idRoom(sqlite3_context*, int, sqlite3_value**)':
xmDatabase.cpp:(.text+0xa251): undefined reference to `sqlite3_value_int'
/usr/bin/ld: xmDatabase.cpp:(.text+0xa292): undefined reference to `sqlite3_result_int'
collect2: error: ld returned 1 exit status
make[2]: *** [src/CMakeFiles/xmoto.dir/build.make:3086: src/xmoto] Error 1
make[1]: *** [CMakeFiles/Makefile2:302: src/CMakeFiles/xmoto.dir/all] Error 2
make: *** [Makefile:156: all] Error 2
[.....@localhost build]$ 
