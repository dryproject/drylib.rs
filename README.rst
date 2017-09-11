***************
DRYlib for Rust
***************

.. image:: https://img.shields.io/badge/license-Public%20Domain-blue.svg
   :alt: Project license
   :target: https://unlicense.org/

.. image:: https://img.shields.io/travis/dryproject/drylib.rs/master.svg
   :alt: Travis CI build status
   :target: https://travis-ci.org/dryproject/drylib.rs

|

http://drylib.org

Prerequisites
=============

* `Rust <https://en.wikipedia.org/wiki/Rust_(programming_language)>`__
  1.20+

Features
========

Caveats
=======

Installation
============

Usage
=====

::

   extern crate drylib as dry;

Reference
=========

``core``
--------

=============== ================================================================
DRY Symbol      Rust Symbol
=============== ================================================================
``bool``        ``dry::Bool`` (type alias for ``bool``)
``char``        ``dry::Char`` (type alias for ``char``)
``complex``     ``dry::Complex`` (struct)
``float``       ``dry::Float`` (type alias for ``dry::Float64``)
``float32``     ``dry::Float32`` (type alias for ``f32``)
``float64``     ``dry::Float64`` (type alias for ``f64``)
``int``         ``dry::Int`` (type alias for ``isize``)
``int8``        ``dry::Int8`` (type alias for ``i8``)
``int16``       ``dry::Int16`` (type alias for ``i16``)
``int32``       ``dry::Int32`` (type alias for ``i32``)
``int64``       ``dry::Int64`` (type alias for ``i64``)
``int128``      ``dry::Int128`` (type alias for ``dry::Integer``)
``integer``     ``dry::Integer`` (struct)
``natural``     ``dry::Natural`` (type alias for ``dry::Integer``)
``rational``    ``dry::Rational`` (struct)
``real``        ``dry::Real`` (struct)
``word``        ``dry::Word`` (type alias for ``usize``)
``word8``       ``dry::Word8`` (type alias for ``u8``)
``word16``      ``dry::Word16`` (type alias for ``u16``)
``word32``      ``dry::Word32`` (type alias for ``u32``)
``word64``      ``dry::Word64`` (type alias for ``u64``)
=============== ================================================================
