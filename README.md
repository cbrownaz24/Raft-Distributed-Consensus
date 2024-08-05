<p>
  A fault-tolerant key-value storage service using a Raft library.
  The key-value service is structured as a replicated state machine 
  with several key-value servers that coordinate their activities
  through the Raft log. The key/value service continues to
  process client requests as long as a majority of the servers
  are alive and can communicate, in spite of other failures or
  network partitions.
</p>
