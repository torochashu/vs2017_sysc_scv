# vs2017_sysc_scv
SystemC 2.3.2 and SCV 2.0.1 libraries compiled with Microsoft Visual Studio Community 2017.  View the wiki for more information.

### To-Do's:
* Compile SystemC Verification Library (SCV) in VS2017.  Project file included with distribution is super old (MSVC 8.0)
* Test modified SCV install on Cygwin.  Default installation fails saying "gcc 6.4 is not a supported version" and "configure: error: cygwin is not supported."
* Try adding "6.4" to SUPPORTED_CXX_VERSIONS in line 16084 in scv-2.0.1/configure
* Try adding "cygwin" to "$target_os" in line 16111 in scv-2.0.1/configure
* see http://forums.accellera.org/topic/5613-scv-library-with-cygwin/

