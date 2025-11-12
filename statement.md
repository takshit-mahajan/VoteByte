Indian Political System
Problem Statement
In India, elections are conducted across multiple states and constituencies. Votes are cast, counted, and stored in digital machines as binary data. In this assignment, you will:

Model the Indian Political System using OOP (parties, candidates, elections).


Store candidate data in binary format using bytes and bytearray.


Demonstrate single-level inheritance (e.g., ElectionCommission → StateElectionCommission).


Work with different data types (string, integer, float, boolean) and convert them to bytes.


Write functions to encode/decode data from bytes into human-readable format.

Simulate vote casting and results using binary data.
Tasks
Part A: Modeling Political System with Inheritance
Create a base class ElectionCommission with attributes:
country (string)
total_states (int)
Method: display_info()
Create a derived class StateElectionCommission inheriting from ElectionCommission. Add attributes:
state_name (string)
num_constituencies (int)
Method: display_state_info()

Part B: Candidate Data in Bytes
Create a Candidate class with attributes:
candidate_id (int)
name (string)
party (string)
age (int)
is_incumbent (boolean)
vote_share (float)

Write a function encode_candidate_to_bytes() that converts candidate details into a bytes object.
Write another function decode_candidate_from_bytes() that takes bytes and reconstructs candidate details.

Part C: Working with Bytearray
Store votes in a bytearray, where:
Each byte represents votes received in one constituency.
Example: bytearray([120, 200, 75]) → Candidate got 120, 200, 75 votes in 3 constituencies.
Write a function calculate_total_votes() to compute the sum of votes from bytearray.
Write a function update_votes() that modifies the bytearray (simulating real-time vote updates).

