import React, { useState } from 'react';

function App() {
  const [likes, setLikes] = useState(0);

  return (
    <div style={{ padding: '40px' }}>
      <h1>Develop. Preview. Ship.</h1>
      <ul>
        <li>Ada Lovelace</li>
        <li>Grace Hopper</li>
        <li>Margaret Hamilton</li>
      </ul>
      <button onClick={() => setLikes(likes + 1)}>
        Like ({likes})
      </button>
    </div>
  );
}

export default App;

# Nextjs
