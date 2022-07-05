# Blockchain
1. Built the PyChain ledger following the starter code which had the functionality to create blocks, perform the proof of work consensus protocol, and validate blocks in the chain. Below are the steps:
2. Created a Record Data Class:
    * Defined a new class named `Record`.
    * Added the @dataclass decorator immediately before the Record class definition.
    * Added attributes named sender and receiver of type str and amount of type float
3. Modified the Existing Block Data Class to Store Record Data: Renamed the data attribute in the Block class to record
4. Add Relevant User Inputs to the Streamlit Interface: Coded additional input areas for the user interface of theStreamlit application. Created these input areas to capture the sender, receiver, and amount for each transaction that is stored in the Block record. 
5. Test the PyChain Ledger by Storing Records: Tested the complete PyChain ledger and user interface by running your Streamlit application and storing some mined blocks in the PyChain ledger.
6. Attachmnents:
    * Starter Code (py file)
    * Python file for Streamlit deployment
    * Screen recording of streamlit deployment
    * Screenshot of Streamlit deployment:
![image](https://github.com/nhc12/Blockchain/blob/main/PyChain%20Screenshot1.jpg)

    
