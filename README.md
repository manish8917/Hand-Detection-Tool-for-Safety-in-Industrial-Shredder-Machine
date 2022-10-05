# Safety-Tool-for-Shredder-Machine

Consumer Product Safety Commission data indicate that over 2,000 people were treated in hospitals for business and office machine injuries during 2007. Lacerations to fingers from paper shredders and other shredder accidents were among these injuries. Most injuries were caused by operator inattention or error.

As an Attempt to solve the above problem this project was developed to alert when the hand moves beyond a certain limit into the shredder machine. When the hand is reaching near the blades of the machine and cross the second threshold the machine is set to auto cutoff.

The model is trained on SSD mobile net, the data was collected from a recording of 24 hours of workers working with the shredder. The data was then augmented and validated using Data augmentation techniques. The data was then annotated and trained using faster RCNN and Mobilenet SSD model, as Mobile net gave better results it was chosen for productionizing.The code is available in master branch of the repository.

# Problem Statement Example:

![mks](https://user-images.githubusercontent.com/40944253/194013764-d0f9205c-8008-4000-b974-cafc9f72415c.png)
