primary_plane: 3
reads_from: [2, 3, 4, 5]
writes_to: [2, 3, 4]
floor: 2
ceiling: 5
reasoning: |
  Comms Engineer builds protocols between planes. Operates at Plane 3 (structured IR)
  because protocols need type safety. Writes test vectors at Plane 2 and documentation
  at Plane 4.
