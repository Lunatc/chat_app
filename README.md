# Chat App

##Requirements

<details><summary>Functional Requirements</summary>

1. Messaging:
	- One-to-one messaging;
	- Delivery status(sent, delivered, read);
	- (?)Group messaging.
2. End-to-End Encryption:
	- Encrypt messages on the sender’s device and decrypt them on the receiver’s device;
	- Generate and manage encryption keys securely.
3. File Sharing:
	- Secure sharing of files (images, videos, documents, audio) with encryption.
4. Interface:
	- Dark/light mode;
	- 
4. (?)Notifications:
	- Real-time notifications for new messages.
5. (?)User Authentication and Registration
	- Users should be able to register and authenticate using secure methods (e.g., OAuth, two-factor authentication).
	- Unique identification for each user;
6. (?)Contact Management:
	- Users can add, remove, and manage contacts;
	- Users can see their contacts' online/offline status.	

</details>

<details><summary>Non-Functional Requirements</summary>

1. Security:
	- Implement end-to-end encryption;
	- Secure key management;
	- Secure storage for sensitive information on the device;
	- Use HTTPS for all communications with servers;
	- Regular security audits and vulnerability assessments.
2. Usability:
	- Intuitive and user-friendly interface;
	- Accessible design for users with disabilities;
	- (?)Multi-language support.
3. Performance:
	- Efficient encryption/decryption algorithms to ensure minimal latency;
	- Scalability to handle a large number of users and messages.
4. Reliability:	
	- Ensure message delivery even under poor network conditions;
	- Implement mechanisms for message synchronization across devices.

</details>

