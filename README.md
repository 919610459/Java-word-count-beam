https://beam.apache.org/get-started/quickstart-java/

mvn archetype:generate `
  -D archetypeGroupId=org.apache.beam `
  -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
  -D archetypeVersion=2.42.0 `
  -D groupId=org.example `
  -D artifactId=word-count-beam `
  -D version="0.1" `
  -D package=org.apache.beam.examples `
  -D interactiveMode=false
   
cd .\word-count-beam

dir .\src\main\java\org\apache\beam\examples

In the word-count-beam directory, create a file called sample.txt. Add some text to the file. For this example

mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner

ls counts*
   
more counts*

Output :

sent: 1
word: 1
despised: 1
patient: 1
nick: 1
proud: 2
distracted: 1
devotion: 1
Niggard: 1
pangs: 1
KING: 9
who: 2
ugly: 1
behaved: 1
sugar: 1
How: 3
much: 3
suffer: 1
You: 2
consummation: 1
Affront: 1
why: 2
confession: 1
restore: 1
Soft: 1
I: 32
turn: 1
wantonness: 1
whose: 1
fit: 1
God: 2
reply: 1
by: 6
as: 10
translate: 1
ay: 1
more: 7
plague: 1
delights: 1
ROSENCRANTZ: 7
an: 1
for: 10
act: 1
tis: 3
turbulent: 1
go: 4
yours: 1
givers: 1
room: 1
needs: 1
Exeunt: 3
scholar: 1
observers: 1
am: 2
order: 1
better: 2
breeder: 1
quietus: 1
with: 11
ecstasy: 1
borne: 1
could: 1
judge: 1
some: 2
speak: 1
Whereon: 1
heaven: 1
too: 5
Read: 1
ha: 1
placed: 1
dreams: 1
shall: 11
relish: 1
may: 6
hither: 1
dangerous: 1
brood: 1
Blasted: 1
walk: 1
expel: 1
breath: 1
make: 5
seen: 2
affliction: 1
Or: 2
danger: 1
takes: 1
reason: 1
send: 1
receive: 2
disclose: 1
already: 2
and: 31
closely: 1
This: 2
those: 2
To: 16
perchance: 1
Nor: 2
art: 1
merit: 1
speech: 1
think: 3
nobler: 1
believe: 3
things: 2
wax: 1
GUILDENSTERN: 4
fellows: 1
bare: 1
way: 3
all: 10
ignorance: 1
What: 3
madness: 2
revengeful: 1
book: 1
force: 1
thoughts: 1
once: 1
doors: 1
Her: 1
chaste: 1
soldier: 1
knaves: 1
love: 4
bawd: 1
exercise: 1
tribute: 1
imagination: 1
When: 3
Sprung: 1
fair: 4
opposing: 1
