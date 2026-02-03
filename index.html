import { useState, useEffect } from "react";

const TERMS = [
  { term:"Variable",                       def:"A named container that stores a value in a program" },
  { term:"Data Type",                      def:"The classification of a value (e.g., int, str, list)" },
  { term:"Integer (int)",                  def:"A whole number with no decimal point" },
  { term:"Float",                          def:"A number that includes a decimal point" },
  { term:"String",                         def:"A sequence of characters enclosed in quotes" },
  { term:"Boolean",                        def:"A data type with only two values: True or False" },
  { term:"List",                           def:"An ordered, mutable collection enclosed in square brackets" },
  { term:"Tuple",                          def:"An ordered, immutable collection enclosed in parentheses" },
  { term:"Dictionary",                     def:"A collection of key-value pairs enclosed in curly braces" },
  { term:"Set",                            def:"An unordered collection of unique values in curly braces" },
  { term:"None",                           def:"Python's way of representing the absence of a value" },
  { term:"If Statement",                   def:"Executes a block of code when a condition is True" },
  { term:"Elif",                           def:"Tests an additional condition after a failed if or elif" },
  { term:"Else",                           def:"Runs a block of code when all prior conditions are False" },
  { term:"For Loop",                       def:"Repeats a block of code for each item in a sequence" },
  { term:"While Loop",                     def:"Repeats a block of code as long as a condition is True" },
  { term:"Break",                          def:"Immediately exits out of a loop" },
  { term:"Continue",                       def:"Skips the rest of the loop and moves to the next iteration" },
  { term:"Pass",                           def:"A placeholder that does nothing; avoids empty blocks" },
  { term:"Function (def)",                 def:"A reusable block of code defined with the def keyword" },
  { term:"Return Statement",              def:"Sends a value back from a function to the caller" },
  { term:"Lambda",                         def:"A short, anonymous function written on a single line" },
  { term:"*args",                          def:"Lets a function accept any number of positional arguments" },
  { term:"**kwargs",                       def:"Lets a function accept any number of keyword arguments" },
  { term:"Default Parameter",             def:"A parameter with a pre-assigned value in a function" },
  { term:"Recursion",                      def:"When a function calls itself to solve a smaller sub-problem" },
  { term:"Nested Function",               def:"A function defined inside another function" },
  { term:"Closure",                        def:"An inner function that remembers values from its outer scope" },
  { term:"Decorator",                      def:"A function that modifies or enhances another function" },
  { term:"Generator",                      def:"A function that yields values one at a time using yield" },
  { term:"Yield",                          def:"Pauses a generator and returns a value to the caller" },
  { term:"Class",                          def:"A blueprint for creating objects with shared behavior" },
  { term:"Object",                         def:"An instance created from a class" },
  { term:"Constructor (__init__)",         def:"The method that runs automatically when an object is created" },
  { term:"Self",                           def:"Refers to the current instance of a class within its methods" },
  { term:"Inheritance",                    def:"A child class takes on attributes and methods of a parent" },
  { term:"Polymorphism",                   def:"Different objects responding to the same method differently" },
  { term:"Encapsulation",                  def:"Bundling data and methods together and restricting access" },
  { term:"Static Method",                  def:"A class method that doesn't use self or cls" },
  { term:"Class Method",                   def:"A method that receives the class itself as its first argument" },
  { term:"Property",                       def:"A decorator that lets a method behave like an attribute" },
  { term:"Abstract Class",                 def:"A class that cannot be instantiated; must be subclassed" },
  { term:"Magic Method",                   def:"Special methods with double underscores (e.g., __str__)" },
  { term:"Multiple Inheritance",           def:"A class that inherits from more than one parent class" },
  { term:"Import",                         def:"A keyword used to bring a module into a program" },
  { term:"Module",                         def:"A single Python file that can be imported and reused" },
  { term:"Package",                        def:"A folder of modules organized with an __init__.py file" },
  { term:"Pip",                            def:"Python's default tool for installing third-party packages" },
  { term:"Virtual Environment",            def:"An isolated space to install packages without system conflict" },
  { term:"Try Block",                      def:"The section of code tested for errors in error handling" },
  { term:"Except Block",                   def:"The section that runs when a specific error is caught" },
  { term:"Finally Block",                  def:"Code that runs whether or not an error occurred" },
  { term:"Raise",                          def:"Used to manually trigger an exception in a program" },
  { term:"Exception",                      def:"An error that occurs and interrupts program execution" },
  { term:"Custom Exception",               def:"A user-defined exception class for specific error types" },
  { term:"Open()",                         def:"A built-in function used to open and access files" },
  { term:"File Modes",                     def:"Codes like 'r', 'w', 'a' that set how a file is accessed" },
  { term:"With Statement",                 def:"Manages resources like files and ensures proper cleanup" },
  { term:"F-String",                       def:"A string that embeds expressions inside curly braces" },
  { term:"String Formatting",              def:"The process of inserting values into a template string" },
  { term:"Raw String",                     def:"A string where backslashes are treated as literal characters" },
  { term:"Multiline String",               def:"A string that spans multiple lines using triple quotes" },
  { term:"Regular Expression",             def:"A pattern used to search or match text in strings" },
  { term:"List Comprehension",             def:"A short syntax to create a list from an existing iterable" },
  { term:"Dict Comprehension",             def:"A short syntax to create a dictionary from an iterable" },
  { term:"Set Comprehension",              def:"A short syntax to create a set from an iterable" },
  { term:"Generator Expression",           def:"Like a list comprehension but produces values one at a time" },
  { term:"Iterator",                       def:"An object that returns values one at a time using next()" },
  { term:"Iterable",                       def:"Any object you can loop over, such as a list or string" },
  { term:"Enumerate",                      def:"A function that pairs each item with its index in a loop" },
  { term:"Zip",                            def:"Combines elements from multiple iterables into tuples" },
  { term:"Map",                            def:"Applies a function to every item in an iterable" },
  { term:"Filter",                         def:"Returns items from an iterable that meet a given condition" },
  { term:"Range",                          def:"Generates a sequence of numbers, mainly used in for loops" },
  { term:"Scope",                          def:"The region of code where a variable is accessible" },
  { term:"Global Keyword",                 def:"Declares a variable inside a function as the global one" },
  { term:"Local Variable",                 def:"A variable defined inside a function, only accessible there" },
  { term:"Nonlocal Keyword",               def:"Lets a nested function modify a variable in its outer scope" },
  { term:"Namespace",                      def:"A container that maps names to objects to avoid conflicts" },
  { term:"Mutable",                        def:"An object whose value can be changed after creation" },
  { term:"Immutable",                      def:"An object whose value cannot be changed once created" },
  { term:"Type Hints",                     def:"Annotations on variables or functions indicating data types" },
  { term:"Docstring",                      def:"A string at the start of a function or class describing it" },
  { term:"Comment",                        def:"Text preceded by # that is ignored by the interpreter" },
  { term:"Index",                          def:"The position number of an element in a sequence, starting at 0" },
  { term:"Slice",                          def:"A way to extract a portion of a sequence using start:stop" },
  { term:"Operator",                       def:"A symbol that performs an operation on one or more values" },
  { term:"Assignment",                     def:"Storing a value in a variable using the = sign" },
  { term:"Comparison Operator",            def:"Symbols like ==, !=, <, > used to compare two values" },
  { term:"Logical Operator",               def:"Keywords (and, or, not) that combine or negate conditions" },
];

const LEVELS = [
  { name:"Easy",   icon:"🌱", pairs: 8, cols:4, cardH:152 },
  { name:"Medium", icon:"🌿", pairs:12, cols:6, cardH:140 },
  { name:"Hard",   icon:"🔥", pairs:16, cols:8, cardH:128 },
];

const TEAM = [
  { color:"#e74c4c", bg:"linear-gradient(150deg, #4a1818, #6e2828)", border:"#e74c4c", glow:"rgba(231,76,76,0.45)" },
  { color:"#4a9eff", bg:"linear-gradient(150deg, #18354a, #28576e)", border:"#4a9eff", glow:"rgba(74,158,255,0.45)" },
  { color:"#f5a623", bg:"linear-gradient(150deg, #4a3518, #6e5228)", border:"#f5a623", glow:"rgba(245,166,35,0.45)" },
  { color:"#c084fc", bg:"linear-gradient(150deg, #3a1848, #5e286e)", border:"#c084fc", glow:"rgba(192,132,252,0.45)" },
];

function shuffle(a) {
  const b = [...a];
  for (let i = b.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [b[i], b[j]] = [b[j], b[i]];
  }
  return b;
}

function makeCards(n) {
  const sel = shuffle(TERMS).slice(0, n);
  return shuffle(
    sel.flatMap((t, i) => [
      { id:`t${i}`, pair:i, isTerm:true,  text:t.term },
      { id:`d${i}`, pair:i, isTerm:false, text:t.def  },
    ])
  );
}

function fmtTime(s) {
  return `${Math.floor(s/60)}:${(s%60).toString().padStart(2,"0")}`;
}

/* ─── CARD ─── */
function Card({ card, visible, matchColor, onClick, cardH }) {
  const [hov, setHov] = useState(false);
  const isMatched = !!matchColor;
  const len = card.text.length;
  const fs  = len > 44 ? 9 : len > 32 ? 9.5 : len > 22 ? 11 : 13;

  return (
    <div
      onClick={onClick}
      onMouseEnter={() => setHov(true)}
      onMouseLeave={() => setHov(false)}
      style={{ perspective:1000, cursor: isMatched?"default":"pointer", height:cardH, userSelect:"none" }}
    >
      <div style={{
        transformStyle:"preserve-3d",
        transition:"transform 0.45s cubic-bezier(.4,0,.2,1)",
        transform: visible ? "rotateY(180deg)" : (hov&&!isMatched) ? "rotateY(6deg)" : "rotateY(0deg)",
        width:"100%", height:"100%", position:"relative",
      }}>
        {/* BACK */}
        <div style={{
          backfaceVisibility:"hidden", position:"absolute", inset:0, borderRadius:10,
          backgroundColor:"#0b4f5c",
          backgroundImage:"radial-gradient(circle, rgba(212,168,67,0.22) 1.3px, transparent 1.3px), linear-gradient(150deg, #0b4f5c 0%, #147a8f 100%)",
          backgroundSize:"16px 16px, 100% 100%",
          border:"2px solid #d4a843",
          display:"flex", alignItems:"center", justifyContent:"center",
          boxShadow: (hov&&!isMatched) ? "0 6px 20px rgba(0,0,0,0.45)" : "0 3px 10px rgba(0,0,0,0.3)",
          transition:"box-shadow 0.2s",
        }}>
          <span style={{ color:"#d4a843", fontSize:28, opacity:0.75, fontWeight:800 }}>?</span>
        </div>
        {/* FRONT */}
        <div style={{
          backfaceVisibility:"hidden", position:"absolute", inset:0, borderRadius:10,
          transform:"rotateY(180deg)",
          background: isMatched
            ? matchColor.bg
            : card.isTerm
              ? "linear-gradient(150deg, #122c4e, #1c3f6e)"
              : "linear-gradient(150deg, #0a4858, #0d6478)",
          border:`2px solid ${isMatched ? matchColor.border : "#d4a843"}`,
          boxShadow: isMatched
            ? `0 0 14px ${matchColor.glow}, 0 3px 10px rgba(0,0,0,0.3)`
            : "0 3px 10px rgba(0,0,0,0.3)",
          display:"flex", flexDirection:"column", alignItems:"center", justifyContent:"center",
          padding:"8px 7px", textAlign:"center",
        }}>
          <div style={{
            fontSize:7.5, textTransform:"uppercase", letterSpacing:2, fontWeight:700,
            color: isMatched ? matchColor.border : (card.isTerm ? "#d4a843" : "#e8c96b"), marginBottom:5,
          }}>
            {card.isTerm ? "▸ Term" : "▸ Definition"}
          </div>
          <div style={{ color:"#fff", fontSize:fs, fontWeight:card.isTerm?700:400, lineHeight:1.35 }}>
            {card.text}
          </div>
        </div>
      </div>
    </div>
  );
}

/* ─── STAT BADGE ─── */
function StatBadge({ label, value, color }) {
  return (
    <span style={{ color:"#ede4cd", display:"flex", alignItems:"baseline", gap:4 }}>
      <span style={{ color, fontWeight:800, fontSize:17 }}>{value}</span>
      <span style={{ opacity:0.5, fontSize:12 }}>{label}</span>
    </span>
  );
}

/* ─── SHARED BUTTON STYLES ─── */
const btnPrimary = {
  background:"linear-gradient(150deg,#0b4f5c,#147a8f)", border:"2px solid #d4a843",
  borderRadius:10, color:"#fff", padding:"13px 30px", cursor:"pointer",
  fontSize:17, fontWeight:700, outline:"none", fontFamily:"'Segoe UI',sans-serif",
};
const btnGhost = {
  background:"transparent", border:"2px solid #d4a843", borderRadius:10,
  color:"#d4a843", padding:"13px 30px", cursor:"pointer",
  fontSize:17, outline:"none", fontFamily:"'Segoe UI',sans-serif",
};

/* ══════════════════════════════════════════════════════════
   APP
   ══════════════════════════════════════════════════════════ */
export default function App() {
  /* ── setup (persists across rounds) ── */
  const [screen,        setScreen]        = useState("start");
  const [selectedLevel, setSelectedLevel] = useState(null);
  const [playerCount,   setPlayerCount]   = useState(1);
  const [playerNames,   setPlayerNames]   = useState(["Player 1","Player 2","Player 3","Player 4"]);

  /* ── active game ── */
  const [level,         setLevel]         = useState(null);
  const [cards,         setCards]         = useState([]);
  const [flipped,       setFlipped]       = useState([]);
  const [matchedBy,     setMatchedBy]     = useState({});   // { pairIdx: ownerIdx }
  const [scores,        setScores]        = useState([0,0,0,0]);
  const [currentPlayer, setCurrentPlayer] = useState(0);
  const [moves,         setMoves]         = useState(0);
  const [secs,          setSecs]          = useState(0);
  const [locked,        setLocked]        = useState(false);
  const [peeking,       setPeeking]       = useState(false);
  const [peekUsed,      setPeekUsed]      = useState(false);

  /* timer */
  useEffect(() => {
    if (screen !== "game") return;
    const t = setInterval(() => setSecs(s => s + 1), 1000);
    return () => clearInterval(t);
  }, [screen]);

  /* launch / reset */
  function launchGame() {
    if (!selectedLevel) return;
    setLevel(selectedLevel);
    setCards(makeCards(selectedLevel.pairs));
    setFlipped([]);
    setMatchedBy({});
    setScores([0,0,0,0]);
    setCurrentPlayer(0);
    setMoves(0); setSecs(0);
    setLocked(false);
    setPeeking(false);
    setPeekUsed(false);
    setScreen("game");
  }

  /* card click */
  function handleClick(i) {
    if (locked || peeking) return;
    if (flipped.includes(i)) return;
    if (cards[i].pair in matchedBy) return;

    const next = [...flipped, i];
    setFlipped(next);

    if (next.length === 2) {
      setLocked(true);
      setMoves(m => m + 1);
      const [a, b] = next;

      if (cards[a].pair === cards[b].pair) {
        /* ── match: score point, keep turn ── */
        const nm = { ...matchedBy, [cards[a].pair]: currentPlayer };
        setMatchedBy(nm);
        const ns = [...scores];
        ns[currentPlayer]++;
        setScores(ns);
        setFlipped([]);
        setLocked(false);
        if (Object.keys(nm).length === level.pairs)
          setTimeout(() => setScreen("win"), 520);
      } else {
        /* ── miss: pass turn ── */
        setTimeout(() => {
          setFlipped([]);
          setLocked(false);
          setCurrentPlayer(cp => (cp + 1) % playerCount);
        }, 1000);
      }
    }
  }

  /* peek */
  function doPeek() {
    if (peekUsed || peeking) return;
    setPeekUsed(true);
    setPeeking(true);
    setTimeout(() => setPeeking(false), 3000);
  }

  /* solo rating */
  function getRating() {
    const r = moves / level.pairs;
    if (r <= 1.3) return { emoji:"🏆", label:"Perfect!",         color:"#ffd700" };
    if (r <= 2.2) return { emoji:"⭐", label:"Excellent!",       color:"#7dd3fc" };
    if (r <= 3.8) return { emoji:"👍", label:"Great Job!",       color:"#86efac" };
    return               { emoji:"📚", label:"Keep Practicing!", color:"#c4b5fd" };
  }

  const matchedCount = Object.keys(matchedBy).length;
  const isSolo       = playerCount === 1;

  const shell = {
    minHeight:"100vh", background:"#0e1b35",
    fontFamily:"'Georgia','Times New Roman',serif",
    display:"flex", flexDirection:"column",
    alignItems:"center", justifyContent:"center", padding:32,
  };

  /* ══════════════════ START SCREEN ══════════════════ */
  if (screen === "start") return (
    <div style={shell}>
      <div style={{ textAlign:"center", maxWidth:760 }}>
        <div style={{ fontSize:52 }}>💻</div>
        <h1 style={{ color:"#d4a843", fontSize:38, margin:"10px 0 0", fontWeight:800, letterSpacing:-0.5 }}>
          Python Term Matcher
        </h1>
        <p style={{ color:"#ede4cd", fontSize:15, margin:"12px 0 0", opacity:0.72, lineHeight:1.6, fontFamily:"'Segoe UI',sans-serif" }}>
          Flip cards to pair each computing term with its definition.<br/>
          Test yourself across <strong style={{ color:"#d4a843" }}>90 essential Python concepts</strong>.
        </p>

        {/* ─── DIFFICULTY ─── */}
        <div style={{ color:"#d4a843", fontSize:11, marginTop:32, marginBottom:10, textTransform:"uppercase", letterSpacing:2.8, fontWeight:700, fontFamily:"'Segoe UI',sans-serif" }}>
          Choose Difficulty
        </div>
        <div style={{ display:"flex", gap:12, justifyContent:"center", flexWrap:"wrap" }}>
          {LEVELS.map(lvl => {
            const sel = selectedLevel?.name === lvl.name;
            return (
              <button key={lvl.name} onClick={() => setSelectedLevel(lvl)} style={{
                background: sel ? "linear-gradient(150deg, #147a8f, #1da8c4)" : "linear-gradient(150deg, #0b4f5c, #147a8f)",
                border:`2px solid ${sel ? "#4ade80" : "#d4a843"}`,
                borderRadius:12, color:"#fff", padding:"14px 22px", cursor:"pointer", textAlign:"center",
                boxShadow: sel ? "0 0 16px rgba(74,222,128,0.35), 0 4px 14px rgba(0,0,0,0.35)" : "0 4px 14px rgba(0,0,0,0.35)",
                transition:"all 0.2s", outline:"none",
              }}
                onMouseEnter={e=>{ if(!sel) e.currentTarget.style.transform="scale(1.05)"; }}
                onMouseLeave={e=>{ e.currentTarget.style.transform="scale(1)"; }}
              >
                <div style={{ fontSize:20 }}>{lvl.icon}</div>
                <div style={{ color:sel?"#4ade80":"#d4a843", fontSize:17, fontWeight:700, marginTop:2 }}>{lvl.name}</div>
                <div style={{ fontSize:12, opacity:0.6, marginTop:2, fontFamily:"'Segoe UI',sans-serif" }}>{lvl.pairs} pairs · {lvl.pairs*2} cards</div>
              </button>
            );
          })}
        </div>

        {/* ─── PLAYER COUNT ─── */}
        <div style={{ color:"#d4a843", fontSize:11, marginTop:30, marginBottom:10, textTransform:"uppercase", letterSpacing:2.8, fontWeight:700, fontFamily:"'Segoe UI',sans-serif" }}>
          Players / Teams
        </div>
        <div style={{ display:"flex", gap:8, justifyContent:"center" }}>
          {[1,2,3,4].map(n => {
            const active = playerCount === n;
            return (
              <button key={n} onClick={() => setPlayerCount(n)} style={{
                width:48, height:48, borderRadius:10, outline:"none", cursor:"pointer",
                background: active ? "linear-gradient(150deg, #147a8f, #1da8c4)" : "rgba(255,255,255,0.06)",
                border:`2px solid ${active ? "#4ade80" : "rgba(212,168,67,0.35)"}`,
                color:"#fff", fontSize:21, fontWeight:700,
                boxShadow: active ? "0 0 14px rgba(74,222,128,0.3)" : "none",
                transition:"all 0.2s",
                display:"flex", alignItems:"center", justifyContent:"center",
              }}>
                {n}
              </button>
            );
          })}
        </div>

        {/* ─── PLAYER NAMES ─── */}
        <div style={{ display:"flex", gap:10, justifyContent:"center", flexWrap:"wrap", marginTop:16 }}>
          {Array.from({ length: playerCount }, (_, i) => (
            <div key={i} style={{ display:"flex", alignItems:"stretch" }}>
              {/* color tab */}
              <div style={{ width:5, borderRadius:"4px 0 0 4px", background: TEAM[i].color }} />
              <input
                value={playerNames[i]}
                onChange={e => {
                  const n = [...playerNames];
                  n[i] = e.target.value || `Player ${i+1}`;
                  setPlayerNames(n);
                }}
                maxLength={16}
                style={{
                  background:"rgba(255,255,255,0.07)",
                  border:`1px solid ${TEAM[i].color}55`,
                  borderLeft:"none",
                  borderRadius:"0 8px 8px 0",
                  color:"#fff", padding:"9px 14px", fontSize:14, width:134,
                  outline:"none", fontFamily:"'Segoe UI',sans-serif",
                }}
              />
            </div>
          ))}
        </div>

        {/* ─── START BUTTON ─── */}
        <button
          onClick={launchGame}
          disabled={!selectedLevel}
          style={{
            marginTop:30,
            background: selectedLevel ? "linear-gradient(150deg, #147a8f, #1da8c4)" : "rgba(255,255,255,0.07)",
            border:`2px solid ${selectedLevel ? "#d4a843" : "rgba(212,168,67,0.25)"}`,
            borderRadius:12, color: selectedLevel ? "#fff" : "rgba(255,255,255,0.35)",
            padding:"15px 56px", cursor: selectedLevel ? "pointer" : "default",
            fontSize:20, fontWeight:700, outline:"none",
            boxShadow: selectedLevel ? "0 4px 20px rgba(0,0,0,0.4)" : "none",
            transition:"all 0.2s", fontFamily:"'Georgia',serif",
          }}
          onMouseEnter={e=>{ if(selectedLevel) e.currentTarget.style.transform="scale(1.04)"; }}
          onMouseLeave={e=>{ e.currentTarget.style.transform="scale(1)"; }}
        >
          Start Game
        </button>

        <p style={{ color:"#ede4cd", fontSize:12, marginTop:22, opacity:0.35, lineHeight:1.7, fontFamily:"'Segoe UI',sans-serif" }}>
          90 terms drawn randomly each round · One free "Peek" hint per game
        </p>
      </div>
    </div>
  );

  /* ══════════════════ WIN SCREEN ══════════════════ */
  if (screen === "win") {
    const maxScore  = Math.max(...scores.slice(0, playerCount));
    const sorted    = Array.from({ length: playerCount }, (_, i) => ({ i, name: playerNames[i], score: scores[i] }))
                            .sort((a, b) => b.score - a.score);
    const winners   = sorted.filter(p => p.score === maxScore);
    const titleText = isSolo ? "You Won!" : winners.length > 1 ? "It's a Tie!" : `${winners[0].name} Wins!`;
    const { emoji, label, color: ratingColor } = isSolo ? getRating() : { emoji:"", label:"", color:"" };

    /* assign medal emoji per rank */
    function medal(rank, score) {
      if (score === maxScore) return "🏆";
      if (rank === 1) return "🥈";
      if (rank === 2) return "🥉";
      return `${rank+1}.`;
    }

    return (
      <div style={shell}>
        <div style={{ textAlign:"center" }}>
          <div style={{ fontSize:76 }}>🎉</div>
          <h1 style={{ color:"#d4a843", fontSize:42, margin:"14px 0 6px", fontWeight:800 }}>{titleText}</h1>

          {/* ── solo rating ── */}
          {isSolo && (
            <div style={{ color: ratingColor, fontSize:22, fontWeight:700, fontFamily:"'Segoe UI',sans-serif", marginBottom:16 }}>
              {emoji} {label}
            </div>
          )}

          {/* ── leaderboard (always shown) ── */}
          <div style={{ display:"flex", flexDirection:"column", gap:9, alignItems:"center", marginTop: isSolo ? 4 : 20 }}>
            {sorted.map((p, rank) => {
              const isWin = p.score === maxScore;
              const tc    = TEAM[p.i];
              return (
                <div key={p.i} style={{
                  display:"flex", alignItems:"center", justifyContent:"space-between", gap:16,
                  background: isWin ? `${tc.color}1c` : "rgba(255,255,255,0.05)",
                  border:`2px solid ${isWin ? tc.color : "rgba(255,255,255,0.1)"}`,
                  borderRadius:12, padding:"11px 24px", width:290,
                  boxShadow: isWin ? `0 0 18px ${tc.glow}` : "none",
                }}>
                  <div style={{ display:"flex", alignItems:"center", gap:11 }}>
                    <span style={{ fontSize:21, minWidth:24, textAlign:"center" }}>{medal(rank, p.score)}</span>
                    <span style={{ width:11, height:11, borderRadius:"50%", background: tc.color, flexShrink:0 }} />
                    <span style={{ color:"#fff", fontSize:16, fontWeight:600, fontFamily:"'Segoe UI',sans-serif" }}>{p.name}</span>
                  </div>
                  <span style={{ color: tc.color, fontSize:20, fontWeight:800, fontFamily:"'Segoe UI',sans-serif" }}>
                    {p.score} <span style={{ fontSize:12, opacity:0.55, color:"#ede4cd" }}>pts</span>
                  </span>
                </div>
              );
            })}
          </div>

          {/* ── time row ── */}
          <div style={{ display:"flex", gap:44, justifyContent:"center", marginTop:24 }}>
            {isSolo && (
              <div>
                <div style={{ color:"#d4a843", fontSize:34, fontWeight:800 }}>{moves}</div>
                <div style={{ color:"#ede4cd", fontSize:13, opacity:0.55, fontFamily:"'Segoe UI',sans-serif" }}>Moves</div>
              </div>
            )}
            <div>
              <div style={{ color:"#d4a843", fontSize:34, fontWeight:800 }}>{fmtTime(secs)}</div>
              <div style={{ color:"#ede4cd", fontSize:13, opacity:0.55, fontFamily:"'Segoe UI',sans-serif" }}>Time</div>
            </div>
          </div>

          {/* ── buttons ── */}
          <div style={{ display:"flex", gap:14, marginTop:30, justifyContent:"center" }}>
            <button onClick={launchGame} style={btnPrimary}>🔄 Play Again</button>
            <button onClick={() => setScreen("start")} style={btnGhost}>Menu</button>
          </div>
        </div>
      </div>
    );
  }

  /* ══════════════════ GAME SCREEN ══════════════════ */
  return (
    <div style={{ minHeight:"100vh", background:"#0e1b35", fontFamily:"'Segoe UI',system-ui,sans-serif", padding:"16px 18px 30px" }}>

      {/* ─── SCOREBOARD ─── */}
      <div style={{ maxWidth:940, margin:"0 auto 6px" }}>
        {/* player chips */}
        <div style={{ display:"flex", gap:8, justifyContent:"center", flexWrap:"wrap", marginBottom:10 }}>
          {Array.from({ length: playerCount }, (_, i) => {
            const isActive = currentPlayer === i;
            const tc = TEAM[i];
            return (
              <div key={i} style={{
                display:"flex", alignItems:"center", gap:7,
                background: isActive ? `${tc.color}1e` : "rgba(255,255,255,0.05)",
                border:`2px solid ${isActive ? tc.color : "rgba(255,255,255,0.12)"}`,
                borderRadius:10, padding:"7px 14px",
                boxShadow: isActive ? `0 0 14px ${tc.glow}` : "none",
                transition:"all 0.3s",
              }}>
                <span style={{ width:10, height:10, borderRadius:"50%", background: tc.color, flexShrink:0 }} />
                <span style={{ color:"#fff", fontSize:14, fontWeight: isActive ? 700 : 500 }}>{playerNames[i]}</span>
                <span style={{ color: tc.color, fontSize:17, fontWeight:800 }}>{scores[i]}</span>
                {isActive && <span style={{ fontSize:9.5, color: tc.color, fontWeight:700, marginLeft:1, letterSpacing:0.8 }}>▸ TURN</span>}
              </div>
            );
          })}
        </div>

        {/* stats + controls row */}
        <div style={{ display:"flex", justifyContent:"space-between", alignItems:"center", flexWrap:"wrap", gap:10 }}>
          <div style={{ display:"flex", gap:20 }}>
            {isSolo && <StatBadge label="Moves" value={moves} color="#d4a843" />}
            <StatBadge label="Time"    value={fmtTime(secs)}             color="#d4a843" />
            <StatBadge label="Matched" value={`${matchedCount}/${level.pairs}`} color="#4ade80" />
          </div>
          <div style={{ display:"flex", gap:8 }}>
            {!peekUsed && (
              <button onClick={doPeek} disabled={peeking} style={{
                background: peeking ? "rgba(74,222,128,0.15)" : "rgba(212,168,67,0.12)",
                border:`1px solid ${peeking?"#4ade80":"#d4a843"}`,
                borderRadius:8, color: peeking?"#4ade80":"#d4a843",
                padding:"7px 14px", cursor: peeking?"default":"pointer",
                fontSize:13, fontWeight:600, outline:"none",
              }}>
                {peeking ? "👁 Peeking…" : "👁 Peek"}
              </button>
            )}
            <button onClick={launchGame} style={{ background:"linear-gradient(150deg,#0b4f5c,#147a8f)", border:"1px solid #d4a843", borderRadius:8, color:"#fff", padding:"7px 16px", cursor:"pointer", fontSize:13, fontWeight:600, outline:"none" }}>🔄 New</button>
            <button onClick={() => setScreen("start")} style={{ background:"transparent", border:"1px solid rgba(212,168,67,0.4)", borderRadius:8, color:"#d4a843", padding:"7px 16px", cursor:"pointer", fontSize:13, outline:"none" }}>Menu</button>
          </div>
        </div>
      </div>

      {/* ─── PROGRESS BAR ─── */}
      <div style={{ maxWidth:940, margin:"0 auto 14px", height:5, background:"#1e3555", borderRadius:3, overflow:"hidden" }}>
        <div style={{ height:"100%", width:`${(matchedCount/level.pairs)*100}%`, background:"linear-gradient(90deg, #147a8f, #4ade80)", transition:"width 0.4s ease", borderRadius:3 }} />
      </div>

      {/* ─── CARD GRID ─── */}
      <div style={{ display:"grid", gridTemplateColumns:`repeat(${level.cols}, 1fr)`, gap:10, maxWidth:940, margin:"0 auto" }}>
        {cards.map((card, i) => {
          const isMatched = card.pair in matchedBy;
          return (
            <Card
              key={card.id}
              card={card}
              visible={flipped.includes(i) || isMatched || peeking}
              matchColor={isMatched ? TEAM[matchedBy[card.pair]] : null}
              onClick={() => handleClick(i)}
              cardH={level.cardH}
            />
          );
        })}
      </div>
    </div>
  );
}
