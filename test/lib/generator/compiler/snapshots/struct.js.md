# Snapshot report for `test/lib/generator/compiler/struct.js`

The actual snapshot is saved in `struct.js.snap`.

Generated by [AVA](https://ava.li).

## structGenerator

> Snapshot 1

    `␊
    let TestStruct$TypeCache = null;␊
    const TestStruct$bonks = Symbol('bonks');␊
    const TestStruct$bonk = Symbol('bonk');␊
    const TestStruct$newbyte = Symbol('newbyte');␊
    const TestStruct$newshort = Symbol('newshort');␊
    const TestStruct$mySet = Symbol('mySet');␊
    const TestStruct$types = Symbol('types');␊
    ␊
    export class TestStruct extends Struct {␊
      constructor(args) {␊
        super();␊
        this[TestStruct$bonks] = null;␊
        this[TestStruct$bonk] = null;␊
        this[TestStruct$newbyte] = null;␊
        this[TestStruct$newshort] = 123;␊
        this[TestStruct$mySet] = null;␊
        this[TestStruct$types] = null;␊
        if (args) {␊
          this.bonks = args.bonks;␊
          this.bonk = args.bonk;␊
          this.newbyte = args.newbyte;␊
          this.newshort = args.newshort;␊
          this.mySet = args.mySet;␊
          this.types = args.types;␊
        }␊
      }␊
    ␊
      get bonks() { return this[TestStruct$bonks]; }␊
      set bonks(val) {␊
        this[TestStruct$bonks] = this[$convertToTypedValue](val, { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Bonk } }, 'bonks');␊
      }␊
    ␊
      get bonk() { return this[TestStruct$bonk]; }␊
      set bonk(val) {␊
        this[TestStruct$bonk] = this[$convertToTypedValue](val, { name: 'struct', typeClass: Bonk }, 'bonk');␊
      }␊
    ␊
      get newbyte() { return this[TestStruct$newbyte]; }␊
      set newbyte(val) {␊
        this[TestStruct$newbyte] = this[$convertToTypedValue](val, { name: 'i8', typeClass: null }, 'newbyte');␊
      }␊
    ␊
      get newshort() { return this[TestStruct$newshort]; }␊
      set newshort(val) {␊
        this[TestStruct$newshort] = this[$convertToTypedValue](val, { name: 'i16', typeClass: null }, 'newshort');␊
      }␊
    ␊
      get mySet() { return this[TestStruct$mySet]; }␊
      set mySet(val) {␊
        this[TestStruct$mySet] = this[$convertToTypedValue](val, { name: 'set', typeClass: TSet, valueType: { name: 'struct', typeClass: Bonk } }, 'mySet');␊
      }␊
    ␊
      get types() { return this[TestStruct$types]; }␊
      set types(val) {␊
        this[TestStruct$types] = this[$convertToTypedValue](val, { name: 'map', typeClass: TMap, keyType: { name: 'i32', typeClass: null }, valueType: { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Numbers } } }, 'types');␊
      }␊
    ␊
      static get Type() {␊
        if (TestStruct$TypeCache) return TestStruct$TypeCache;␊
        TestStruct$TypeCache = new Map();␊
        TestStruct$TypeCache.set(1, { name: 'bonks', customName: 'bonks', type: { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Bonk } } });␊
        TestStruct$TypeCache.set(2, { name: 'bonk', customName: 'bonk', type: { name: 'struct', typeClass: Bonk } });␊
        TestStruct$TypeCache.set(3, { name: 'newbyte', customName: 'newbyte', type: { name: 'i8', typeClass: null } });␊
        TestStruct$TypeCache.set(4, { name: 'newshort', customName: 'newshort', type: { name: 'i16', typeClass: null } });␊
        TestStruct$TypeCache.set(5, { name: 'my_set', customName: 'mySet', type: { name: 'set', typeClass: TSet, valueType: { name: 'struct', typeClass: Bonk } } });␊
        TestStruct$TypeCache.set(6, { name: 'types', customName: 'types', type: { name: 'map', typeClass: TMap, keyType: { name: 'i32', typeClass: null }, valueType: { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Numbers } } } });␊
        return TestStruct$TypeCache;␊
      }␊
    }␊
    `

> Snapshot 2

    `␊
    let TestStruct$TypeCache = null;␊
    const TestStruct$BONKS = Symbol('BONKS');␊
    const TestStruct$BONK = Symbol('BONK');␊
    const TestStruct$NEWBYTE = Symbol('NEWBYTE');␊
    const TestStruct$NEWSHORT = Symbol('NEWSHORT');␊
    const TestStruct$MY_SET = Symbol('MY_SET');␊
    const TestStruct$TYPES = Symbol('TYPES');␊
    ␊
    class TestStruct extends Struct {␊
      constructor(args) {␊
        super();␊
        this[TestStruct$BONKS] = null;␊
        this[TestStruct$BONK] = null;␊
        this[TestStruct$NEWBYTE] = null;␊
        this[TestStruct$NEWSHORT] = 123;␊
        this[TestStruct$MY_SET] = null;␊
        this[TestStruct$TYPES] = null;␊
        if (args) {␊
          this.BONKS = args.BONKS;␊
          this.BONK = args.BONK;␊
          this.NEWBYTE = args.NEWBYTE;␊
          this.NEWSHORT = args.NEWSHORT;␊
          this.MY_SET = args.MY_SET;␊
          this.TYPES = args.TYPES;␊
        }␊
      }␊
    ␊
      get BONKS() { return this[TestStruct$BONKS]; }␊
      set BONKS(val) {␊
        this[TestStruct$BONKS] = this[$convertToTypedValue](val, { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Bonk } }, 'BONKS');␊
      }␊
    ␊
      get BONK() { return this[TestStruct$BONK]; }␊
      set BONK(val) {␊
        this[TestStruct$BONK] = this[$convertToTypedValue](val, { name: 'struct', typeClass: Bonk }, 'BONK');␊
      }␊
    ␊
      get NEWBYTE() { return this[TestStruct$NEWBYTE]; }␊
      set NEWBYTE(val) {␊
        this[TestStruct$NEWBYTE] = this[$convertToTypedValue](val, { name: 'i8', typeClass: null }, 'NEWBYTE');␊
      }␊
    ␊
      get NEWSHORT() { return this[TestStruct$NEWSHORT]; }␊
      set NEWSHORT(val) {␊
        this[TestStruct$NEWSHORT] = this[$convertToTypedValue](val, { name: 'i16', typeClass: null }, 'NEWSHORT');␊
      }␊
    ␊
      get MY_SET() { return this[TestStruct$MY_SET]; }␊
      set MY_SET(val) {␊
        this[TestStruct$MY_SET] = this[$convertToTypedValue](val, { name: 'set', typeClass: TSet, valueType: { name: 'struct', typeClass: Bonk } }, 'MY_SET');␊
      }␊
    ␊
      get TYPES() { return this[TestStruct$TYPES]; }␊
      set TYPES(val) {␊
        this[TestStruct$TYPES] = this[$convertToTypedValue](val, { name: 'map', typeClass: TMap, keyType: { name: 'i32', typeClass: null }, valueType: { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Numbers } } }, 'TYPES');␊
      }␊
    ␊
      static get Type() {␊
        if (TestStruct$TypeCache) return TestStruct$TypeCache;␊
        TestStruct$TypeCache = new Map();␊
        TestStruct$TypeCache.set(1, { name: 'bonks', customName: 'BONKS', type: { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Bonk } } });␊
        TestStruct$TypeCache.set(2, { name: 'bonk', customName: 'BONK', type: { name: 'struct', typeClass: Bonk } });␊
        TestStruct$TypeCache.set(3, { name: 'newbyte', customName: 'NEWBYTE', type: { name: 'i8', typeClass: null } });␊
        TestStruct$TypeCache.set(4, { name: 'newshort', customName: 'NEWSHORT', type: { name: 'i16', typeClass: null } });␊
        TestStruct$TypeCache.set(5, { name: 'my_set', customName: 'MY_SET', type: { name: 'set', typeClass: TSet, valueType: { name: 'struct', typeClass: Bonk } } });␊
        TestStruct$TypeCache.set(6, { name: 'types', customName: 'TYPES', type: { name: 'map', typeClass: TMap, keyType: { name: 'i32', typeClass: null }, valueType: { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Numbers } } } });␊
        return TestStruct$TypeCache;␊
      }␊
    }␊
    exports.TestStruct = TestStruct;␊
    `

> Snapshot 3

    `␊
    let TestStruct$TypeCache = null;␊
    const TestStruct$bonks = Symbol('bonks');␊
    const TestStruct$bonk = Symbol('bonk');␊
    const TestStruct$newbyte = Symbol('newbyte');␊
    const TestStruct$newshort = Symbol('newshort');␊
    const TestStruct$my_set = Symbol('my_set');␊
    const TestStruct$types = Symbol('types');␊
    ␊
    class TestStruct extends Struct {␊
      constructor(args) {␊
        super();␊
        this[TestStruct$bonks] = null;␊
        this[TestStruct$bonk] = null;␊
        this[TestStruct$newbyte] = null;␊
        this[TestStruct$newshort] = 123;␊
        this[TestStruct$my_set] = null;␊
        this[TestStruct$types] = null;␊
        if (args) {␊
          this.bonks = args.bonks;␊
          this.bonk = args.bonk;␊
          this.newbyte = args.newbyte;␊
          this.newshort = args.newshort;␊
          this.my_set = args.my_set;␊
          this.types = args.types;␊
        }␊
      }␊
    ␊
      get bonks() { return this[TestStruct$bonks]; }␊
      set bonks(val) {␊
        this[TestStruct$bonks] = this[$convertToTypedValue](val, { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Bonk } }, 'bonks');␊
      }␊
    ␊
      get bonk() { return this[TestStruct$bonk]; }␊
      set bonk(val) {␊
        this[TestStruct$bonk] = this[$convertToTypedValue](val, { name: 'struct', typeClass: Bonk }, 'bonk');␊
      }␊
    ␊
      get newbyte() { return this[TestStruct$newbyte]; }␊
      set newbyte(val) {␊
        this[TestStruct$newbyte] = this[$convertToTypedValue](val, { name: 'i8', typeClass: null }, 'newbyte');␊
      }␊
    ␊
      get newshort() { return this[TestStruct$newshort]; }␊
      set newshort(val) {␊
        this[TestStruct$newshort] = this[$convertToTypedValue](val, { name: 'i16', typeClass: null }, 'newshort');␊
      }␊
    ␊
      get my_set() { return this[TestStruct$my_set]; }␊
      set my_set(val) {␊
        this[TestStruct$my_set] = this[$convertToTypedValue](val, { name: 'set', typeClass: TSet, valueType: { name: 'struct', typeClass: Bonk } }, 'my_set');␊
      }␊
    ␊
      get types() { return this[TestStruct$types]; }␊
      set types(val) {␊
        this[TestStruct$types] = this[$convertToTypedValue](val, { name: 'map', typeClass: TMap, keyType: { name: 'i32', typeClass: null }, valueType: { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Numbers } } }, 'types');␊
      }␊
    ␊
      static get Type() {␊
        if (TestStruct$TypeCache) return TestStruct$TypeCache;␊
        TestStruct$TypeCache = new Map();␊
        TestStruct$TypeCache.set(1, { name: 'bonks', customName: 'bonks', type: { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Bonk } } });␊
        TestStruct$TypeCache.set(2, { name: 'bonk', customName: 'bonk', type: { name: 'struct', typeClass: Bonk } });␊
        TestStruct$TypeCache.set(3, { name: 'newbyte', customName: 'newbyte', type: { name: 'i8', typeClass: null } });␊
        TestStruct$TypeCache.set(4, { name: 'newshort', customName: 'newshort', type: { name: 'i16', typeClass: null } });␊
        TestStruct$TypeCache.set(5, { name: 'my_set', customName: 'my_set', type: { name: 'set', typeClass: TSet, valueType: { name: 'struct', typeClass: Bonk } } });␊
        TestStruct$TypeCache.set(6, { name: 'types', customName: 'types', type: { name: 'map', typeClass: TMap, keyType: { name: 'i32', typeClass: null }, valueType: { name: 'list', typeClass: TList, valueType: { name: 'struct', typeClass: Numbers } } } });␊
        return TestStruct$TypeCache;␊
      }␊
    }␊
    exports.TestStruct = TestStruct;␊
    `