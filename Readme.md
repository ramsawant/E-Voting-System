# Blockchain Voting System (Django Project)

This is a simple project I made using Python and Django to understand how blockchain works in a voting system. The idea was to use the concept of a blockchain to make the voting process secure and transparent.

## 💡 What this project does

- Allows registered users to cast votes for candidates.
- Every vote becomes a block in the blockchain.
- Uses SHA-256 hashing and proof-of-work to make sure no one can tamper with the vote.
- Shows live vote results based on the blocks in the chain.
- Prevents the same user from voting more than once for the same post.

## ⚙️ Technologies Used

- Python 3
- Django Framework
- SQLite (default DB)
- HTML/CSS for frontend
- Custom blockchain logic (not any external library)

## 🔗 How the Blockchain Works

- Each block stores: who voted, for whom, and for which position.
- Once a block is added, its hash is calculated.
- The next block includes the hash of the previous one, so if anything is changed in between, the whole chain breaks.
- Simple proof-of-work is used to make mining a little difficult.

## 📂 Main Files

- `views.py`: Most of the blockchain logic and vote handling.
- `urls.py`: Routes for vote home and vote page.
- `models.py`: Not much here right now, basic Django structure.
- `templates/`: Contains voting and result pages.

## ▶️ How to Run

1. Make sure Python and Django are installed.
2. Run the server using:
   ```bash
   python manage.py runserver
Simple implementation of blockchain with python. 

http://127.0.0.1:8000/vote_home
This is a learning project, so it's not meant for real elections.

The blockchain is implemented using Python classes, not using any heavy blockchain library.

It helped me understand how data immutability and transparency works in blockchain

Made By -Sairaj Gawade
Computer Engineering Student
Mumbai University
