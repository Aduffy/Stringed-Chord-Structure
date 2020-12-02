# Stringed-Chord-Structure

A proposed structure for a standardized structire for storing chord and fingerings for stringed instruments. 

```javascript 

{
    title: "G Major",
    root: "G",
    type: "Major",
    position: 0,
    shape: [
      { string: 6, fret: 3, finger: 1, note: 'G', interval: "P1" },
      { string: 5, fret: 5, finger: 3, note: 'D', interval: 'P5' },
      { string: 4, fret: 5, finger: 4, note: 'G', interval: 'P1' },
      { string: 3, fret: 4, finger: 2, note: 'B', interval: '3M' }, 
      { string: 2, fret: 3, finger: 1, note: 'D', interval: 'P5' }, 
      { string: 1, fret: 3, finger: 1, note: 'G', interval: 'P1' }
    ],
    barres: [
      { fromString: 6, toString: 1, fret: 3, finger: '1', }
    ]
}

```

