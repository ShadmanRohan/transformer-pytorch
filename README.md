### Implementation Techniques

1. Create a large structure which can be filled in with smaller pieces (EncoderDecoder)

2. Repeated structures should be implemented once and cloned (clones(), Encoder)

3. Any computation involving multiple pieces should be implementated as a class that uses the pieces to perform its task (SublayerConnection, EncoderLayer)

4. 


Attention<sub>1:h</sub> = (query,[key,value]<sub>1:n</sub>) &rarr;  output  
  score(query, key)  
  output = SumAll(score<sub>i</sub> * value<sub>i</sub>)
