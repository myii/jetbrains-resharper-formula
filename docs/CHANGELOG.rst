
Changelog
=========

`1.2.1 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/compare/v1.2.0...v1.2.1>`_ (2020-09-20)
---------------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **windows:** fix typo (\ `9a3167d <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/9a3167da26358e35a2c3433b897d99184aba241c>`_\ )

`1.2.0 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/compare/v1.1.0...v1.2.0>`_ (2020-09-20)
---------------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **defaults:** no choco tar package (\ `d1aa72a <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/d1aa72adebb7feb57d6e10d2646a5e7b71645894>`_\ )

Features
^^^^^^^^


* **windows:** basic windows support (\ `561f344 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/561f344e97521030c01c4995fd813108e9da0f6e>`_\ )

`1.1.0 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/compare/v1.0.2...v1.1.0>`_ (2020-09-20)
---------------------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **windows:** basic windows support (\ `5eec29d <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/5eec29d9a7a7d5c0eccd82d1dbe9db28ad90b8d2>`_\ )

`1.0.2 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/compare/v1.0.1...v1.0.2>`_ (2020-07-28)
---------------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **cmd.run:** wrap url in quotes (zsh) (\ `76d5ef9 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/76d5ef913bf6ae32406008d95efc6f34154836fd>`_\ )

Code Refactoring
^^^^^^^^^^^^^^^^


* **jetbrains:** align all jetbrains formulas (\ `c5e718c <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/c5e718c197aa0d3aefff72a8853024a9a33ec8ef>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** use ``saltimages`` Docker Hub where available [skip ci] (\ `1ddc58f <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/1ddc58f142742a3464982b1bc4f776b28dcffdf1>`_\ )

Styles
^^^^^^


* **libtofs.jinja:** use Black-inspired Jinja formatting [skip ci] (\ `fcb8aeb <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/fcb8aebefea5c66e24416153c1d54360a3b3ea0f>`_\ )

`1.0.1 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/compare/v1.0.0...v1.0.1>`_ (2020-06-15)
---------------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** add new platforms [skip ci] (\ `6bd1309 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/6bd1309892f852e1a0a365c3b2b8ee244884ce27>`_\ )
* **travis:** add notifications => zulip [skip ci] (\ `b534bdf <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/b534bdfea9a02e455f677a43707b1f78fff644b5>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** update format (\ `a2c3697 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/a2c3697a968d7164c6cc960d721c4547006fe4e3>`_\ )

`1.0.0 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/compare/v0.1.0...v1.0.0>`_ (2020-05-19)
---------------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **id:** rename conflicting id (\ `64ef232 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/64ef23266e0362f783af02aa7737d661f3feabf8>`_\ )
* **pcode:** fix rendering error (\ `161cd88 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/161cd883ed07953337f2c072c831cf674765d13c>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** adjust matrix to add ``3000.3`` (\ `71893dc <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/71893dcb0bf9266fd73e92b4ad1464ef17f78eda>`_\ )
* **travis:** update travis tests (\ `e57888d <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/e57888d5ea63b70d2131692ba4f4f2c7d1455e0b>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** add depth one (\ `b6ca2b1 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/b6ca2b1ad0ad3c6237374822246aa575ca8bc583>`_\ )

Features
^^^^^^^^


* **formula:** align to template formula; add ci (\ `4aa3275 <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/4aa327550d789b5af37ef915d0c7c172bed5d83a>`_\ )
* **semantic-release:** standardise for this formula (\ `84b5aab <https://github.com/saltstack-formulas/jetbrains-resharper-formula/commit/84b5aab25b1aa8b6a3c5b86893c5c2ebd11240e6>`_\ )

BREAKING CHANGES
^^^^^^^^^^^^^^^^


* **formula:** Major refactor of formula to bring it in alignment with the
  template-formula. As with all substantial changes, please ensure your
  existing configurations work in the ways you expect from this formula.
