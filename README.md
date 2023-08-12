# Hospital-system
This is a code for a simple hospital system created by cpp.

Hospital System:
Implement the following system for a hospital:
  There are 20 different specializations (e.g. Children, Surgery, etc), For each specialization, there are only 5 available spots (A queue).
  We have just four actions:
       1) Adding a patient
           ○ Read the requested specialization [1-20].
           ○ Read his name and status (0 = regular, 1 urgent).
           ○ If 5 patients exist, apologize and don’t accept.
           ○ If the user is regular, add to the queue's end. Otherwise, add in Begin.
       2) Print patients, for the specializations that have waiting patients.
       3) Dr pick up a patient.
         ○ Read the requested specialization. If there are no patients, inform the doctor.
         ○ Otherwise, ask the patient to go with the Dr Remove from the queue.
       4) Exit the program.
