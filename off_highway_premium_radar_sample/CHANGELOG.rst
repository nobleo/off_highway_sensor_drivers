^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package off_highway_premium_radar_sample
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.5.1 (2024-03-27)
------------------
* Disable irrelevant warnings for Clang
  Anonymous structs are used in PCL for type punning:
  https://github.com/PointCloudLibrary/pcl/issues/2303
  Subobject braces are not needed:
  https://bugs.llvm.org/show_bug.cgi?id=21629
  https://gcc.gnu.org/bugzilla/show_bug.cgi?id=25137
* Remove unnecessary self assignment
* Clarify operation order
* Remove C style cast
* Use explicit initialization
* Remove unused variables
* Add virtual destructor for base class
* Contributors: Robin Petereit
