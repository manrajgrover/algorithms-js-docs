---
title: algorithms-js API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - javascript

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - installation
  - errors

search: true
---

# algorithms-js API

[![Build Status](https://travis-ci.org/manrajgrover/algorithms-js.svg?branch=master)](https://travis-ci.org/manrajgrover/algorithms-js) [![npm](https://img.shields.io/npm/v/algorithms-js.svg?maxAge=2592000?style=flat-square)](https://www.npmjs.com/package/algorithms-js)

algorithms-js is a JavaScript library and it provides JavaScript algorithms and data structures.

## Supported data structures

### Doubly linked list
A doubly linked list is a linked data structure that consists of a set of sequentially linked records called nodes. Each node contains two fields, called links, that are references to the previous and to the next node in the sequence of nodes. For more information see [Doubly linked list](https://en.wikipedia.org/wiki/Doubly_linked_list) on Wikipedia.

> **Example**:
```python
sg = shotgun_api3.Shotgun("https://piedpiper.shotgunstudio.com",
    login="rhendriks",
    password="c0mPre$Hi0n")
sg.find("Shot", filters=[["sg_status_list", "is", "ip"]], fields=["code", "sg_status_list"])
```

> **Output**:
```python
[{'code': 'bunny_020_0170',
  'id': 896,
  'sg_sequence': {'id': 5, 'name': 'bunny_020', 'type': 'Sequence'},
  'sg_status_list': 'ip',
  'type': 'Shot'},
 {'code': 'bunny_020_0200',
  'id': 899,
  'sg_sequence': {'id': 5, 'name': 'bunny_020', 'type': 'Sequence'},
  'sg_status_list': 'ip',
  'type': 'Shot'},
 {'code': 'bunny_030_0080',
  'id': 907,
  'sg_sequence': {'id': 6, 'name': 'bunny_030', 'type': 'Sequence'},
  'sg_status_list': 'ip',
  'type': 'Shot'}]
```python

