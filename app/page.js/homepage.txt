export default function Home() {
  return (
    <div style={{
      background: '#0f0f0f',
      color: 'white',
      fontFamily: 'Arial, sans-serif',
      textAlign: 'center',
      padding: '60px 20px',
      minHeight: '100vh'
    }}>
      <h1 style={{ fontSize: '3.5rem', margin: '0 0 10px', color: '#00ff88' }}>
        nightcrawler1222
      </h1>
      <p style={{ fontSize: '1.5rem', color: '#aaa', margin: '0 0 40px' }}>
        Content Creator • Streamer • YouTuber
      </p>

      <div style={{
        maxWidth: '600px',
        margin: '0 auto',
        lineHeight: '2.5'
      }}>
        <p><a href="https://youtube.com/@nightcrawler1222" target="_blank" style={linkStyle}>📺 Watch My YouTube</a></p>
        <p><a href="https://tiktok.com/@nightcrawler1222" target="_blank" style={linkStyle}>🎵 Follow Me on TikTok</a></p>
        <p><a href="https://instagram.com/nightcrawler1222" target="_blank" style={linkStyle}>📸 See My Instagram</a></p>
      </div>

      <div style={{ marginTop: '50px' }}>
        <a href="https://ko-fi.com/nightcrawler1222" target="_blank" style={{
          background: '#0070f3',
          color: 'white',
          padding: '15px 40px',
          borderRadius: '8px',
          textDecoration: 'none',
          fontSize: '1.3rem',
          fontWeight: 'bold'
        }}>
          💬 $1 — Chat With Me (5 Minutes)
        </a>
      </div>
    </div>
  );
}

const linkStyle = {
  color: '#00aaff',
  fontSize: '1.2rem',
  textDecoration: 'none'
};