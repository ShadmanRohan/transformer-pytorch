### Implementation Techniques

1. Create a large structure which can be filled in with smaller pieces (EncoderDecoder)

2. Repeated structures should be implemented once and cloned (clones(), Encoder)

3. Any computation involving multiple pieces should be implementated as a class that uses the pieces to perform its task (SublayerConnection, EncoderLayer)

4. 
