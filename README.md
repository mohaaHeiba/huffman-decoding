<h1>Huffman Coding in Pure C++</h1>

  <p>
    This project is a <strong>from-scratch implementation</strong> of Huffman Encoding and Decoding using only <strong>native C++</strong>.<br>
    I manually implemented all the data structures and algorithms — <strong>no STL containers, no external libraries</strong>, just pure logic and code.
  </p>

  <h2 class="emoji">🚀 Overview</h2>
  <p>
    Huffman coding is a powerful <strong>lossless compression algorithm</strong>.<br>
    In this project, I built the entire Huffman Tree structure, priority queue system, and encoding/decoding logic completely on my own.
  </p>

  <p>This program:</p>
  <ul>
    <li>Calculates the frequency of each character in the input</li>
    <li>Builds a Huffman Tree manually using a custom linked list-based priority queue</li>
    <li>Encodes the input string into a binary sequence</li>
    <li>Decodes the binary back to the original text</li>
  </ul>

  <h2 class="emoji">🔧 What I Built From Scratch</h2>
  <ul>
    <li>✅ Manual <code>Pair</code> struct for frequency and character tracking</li>
    <li>✅ Custom <code>Node</code> and <code>Queue_Node</code> structures to build the tree and queue</li>
    <li>✅ A <code>Linked_list_Queue</code> class to manage nodes in frequency order — <em>no <code>std::priority_queue</code></em></li>
    <li>✅ A <code>Huffman_Tree</code> class with recursive logic for:
      <ul>
        <li>Building the tree</li>
        <li>Encoding characters and full strings</li>
        <li>Decoding binary Huffman-encoded strings</li>
      </ul>
    </li>
    <li>✅ User input handling, frequency table building, and Huffman output</li>
  </ul>

  <h2 class="emoji">🧱 Data Structures Used</h2>
  <p>All data structures were manually created, including:</p>
  <ul>
    <li><code>Pair</code> — stores frequency and character</li>
    <li><code>Node</code> — represents a node in the Huffman Tree</li>
    <li><code>Queue_Node</code> — used for linked list queue nodes</li>
    <li><code>Linked_list_Queue</code> — manually sorted queue used for building the tree</li>
  </ul>

