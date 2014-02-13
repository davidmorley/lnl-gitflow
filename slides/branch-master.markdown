##<small>the</small> master <small>branch</small>
* always reflects production <!-- .element: class="fragment roll-in" -->
* nobody commits! <!-- .element: class="fragment roll-in" -->
* tags reflect released versions <!-- .element: class="fragment roll-in" -->

Note: The HEAD of master always reflects the version of the code that is currently in production. No developer should ever directly commit to this branch -- it is only updated by merging one of the other branch types (which we will discuss later). Previous released versions of the code are tagged with the release number, so that it is easy to go back in history and see the state of the code for any given release.