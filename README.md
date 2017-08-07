# notedown

a plain text format and script for writing music that can be easily converted into html and css that appears as musical notation

## elements of a piece of music

- staff (staves): five horizontal lines with four spaces between
  - 1-5 (1 is the bottom stave; 5 is the top)
  - ensemble staves
  - measure lines
- instrument
- clef
- time signature
- key signature
- notes
  - whole
  - half
  - quarter
  - eighth
  - sixteenth and thirty-second
  - dotted: add half the value of the note
  - above or below the staff
  - grace notes
- rests
  - whole
  - half
  - quarter
  - eighth
  - dotted: add half the value of the rest
- rhythm markers
  - slurs
  - trills
  - pickup notes (anacrusis)
- dynamics
  - pianissimo
  - piano
  - mezzopiano
  - mezzoforte
  - forte
  - fortissimo
  - crescendo (<)
  - decrescendo (>)

## musical phrases

in notedown, put a blank line between musical phrases

for example, in the song twinkle twinkle little star the first phrase is the words "twinkle twinkle little star"

## notes

put a space between each note

using the example of twinkle twinkle again:

c c g g a a g

notedown is not case-sensitive

notedown's default note length is quarter note

### half notes, whole notes, sixteenth notes, etc

make a note a half note by enclosing the note in asterisks (\*note\*) like yo:

\*c\*

### accidentals

add a sharp to a note with the hashtag symbol (#) immediately following the note like yo:

c#

add a flat to a note with the at symbol (@) immediately following the note:

c@

add a natural to a note with the dollar sign symbol ($) immediately following the note

c$