# Externa-avbrott - ATmega328P
Demonstration av olika typer av externa avbrott för mikrodator ATmega328P i C.

Filen "external_interrupt_demo.zip" utgör ett program som demonstrerar användning av flankstyrda externa avbrott för toggling av lysdioder via tryckknappar.

Filen "pin_change_interrupt_demo.zip" demonstrerar motsvarande program med icke-flankstyrda avbrott (PIN Change Interrupts).

Filen "asm external interrupt demo.zip" demonstrerar flankstyrda externa avbrott i assembler.
Här demonstreras hur en avbrottsrutin inte är något annat än en subrutin (funktion) på en viss adress i programminnet,
i detta fall adress 0x0002 för externt avbrott INT0.

Se video tutorials via länkarna nedan:

Flankstyrda externa avbrott: 
https://youtu.be/gqqMUGeyw2E

Icke-flankstyrda externa avbrott: 
https://youtu.be/_ZN9jcZ_Zqk
