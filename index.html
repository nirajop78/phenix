"use client";
import React, { useState } from "react";

const QUESTIONS = [
  {
    q: "What does Fhenix aim to bring to the Ethereum ecosystem?",
    choices: [
      "Faster transactions",
      "Fully Homomorphic Encryption (FHE) enabling confidential on-chain logic",
      "New layer for NFT minting only",
      "Only zero-knowledge proofs"
    ],
    answer: 1,
    note: "Fhenix focuses on FHE to enable encrypted computation on-chain."
  },
  {
    q: "True or False: Fhenix requires developers to learn a completely new smart contract language distinct from Solidity.",
    choices: ["True", "False"],
    answer: 1,
    note: "Fhenix is EVM-compatible and works with familiar tooling."
  },
  {
    q: "Which of these is enabled by the Fhenix offering called 'CoFHE'?",
    choices: [
      "Computation on encrypted inputs/outputs without revealing raw data",
      "Only off-chain data storage",
      "A new UI for trading tokens only",
      "A hardware-only solution requiring trusted execution environments"
    ],
    answer: 0,
    note: "CoFHE enables encrypted logic, without exposing raw data."
  },
  {
    q: "Which use-case best matches Fhenix's vision?",
    choices: [
      "Regular public token transactions only",
      "Confidential stablecoins, dark-pool style trading, encrypted governance votes",
      "Only gaming apps",
      "Traditional banking off-chain only"
    ],
    answer: 1,
    note: "Fhenix emphasises confidential DeFi, encrypted trading, governance votes, etc."
  },
  {
    q: "According to their manifesto, what barrier is Fhenix trying to overcome for large capital?",
    choices: [
      "Scalability in terms of TPS",
      "Transparency that prevents large scale capital deployment",
      "Lack of metaverse usage",
      "Need for brand new chain hardware"
    ],
    answer: 1,
    note: "They argue confidentiality enables large-scale capital to flow onchain."
  },
  {
    q: "True or False: FHE requires the data to be decrypted before processing smart-contract logic.",
    choices: ["True", "False"],
    answer: 1,
    note: "FHE allows computation on encrypted data without decryption."
  },
  {
    q: "Which infrastructure choice supports Fhenix’s confidentiality model?",
    choices: [
      "Trusted Execution Environments only",
      "Modular rollups + data-availability layers",
      "Centralized servers to validate contracts",
      "Proprietary closed-source chain"
    ],
    answer: 1,
    note: "They cite modular design, rollups, separation of compute from consensus."
  },
  {
    q: "True or False: Developers must give up composability when building confidential smart contracts.",
    choices: ["True", "False"],
    answer: 1,
    note: "Fhenix emphasises privacy while maintaining composability."
  },
  {
    q: "What is the significance of Testnet in Fhenix’s roadmap?",
    choices: [
      "No testnet planned",
      "Testnet live for developers to test encrypted logic ahead of mainnet",
      "Testnet is only for gaming use-cases",
      "Testnet will only support off-chain computations"
    ],
    answer: 1,
    note: "Docs and blog mention testnet and early access."
  },
  {
    q: "Which cryptographic primitive is central to Fhenix's offering?",
    choices: [
      "Zero-knowledge proofs only",
      "Multi-party computation (MPC) only",
      "Fully Homomorphic Encryption (FHE)",
      "Hash-based time locks"
    ],
    answer: 2,
    note: "FHE is the core primitive enabling encrypted compute."
  }
];

export default function FhenixLanding() {
  const [step, setStep] = useState(0);
  const [qIndex, setQIndex] = useState(0);
  const [selected, setSelected] = useState(null);
  const [score, setScore] = useState(0);
  const [showResults, setShowResults] = useState(false);
  const [email, setEmail] = useState("");

  const startQuiz = () => {
    setStep(1);
    setQIndex(0);
    setSelected(null);
    setScore(0);
    setShowResults(false);
  };

  const submitAnswer = () => {
    if (selected === null) return;
    if (selected === QUESTIONS[qIndex].answer) setScore((s) => s + 1);
    setTimeout(() => {
      if (qIndex + 1 < QUESTIONS.length) {
        setQIndex(qIndex + 1);
        setSelected(null);
      } else {
        setShowResults(true);
      }
    }, 400);
  };

  const restart = () => startQuiz();

  return (
    <div className="min-h-screen flex flex-col items-center justify-start text-gray-100 bg-gradient-to-br from-[#0f172a] via-[#081129] to-[#071022] relative overflow-hidden">
      {/* background blobs */}
      <div className="absolute inset-0 pointer-events-none">
        <div className="absolute -left-20 -top-20 w-96 h-96 bg-indigo-600 opacity-20 rounded-full blur-3xl animate-blob" />
        <div className="absolute right-0 top-40 w-80 h-80 bg-cyan-500 opacity-15 rounded-full blur-2xl animate-blob animation-delay-2000" />
        <div className="absolute left-1/2 bottom-[-80px] w-96 h-96 bg-rose-500 opacity-10 rounded-full blur-3xl animate-blob animation-delay-4000" />
      </div>

      {/* header */}
      <header className="relative z-10 w-full max-w-6xl px-6 py-8 flex items-center justify-between">
        <div className="flex items-center gap-4">
          <div className="w-12 h-12 bg-white/10 rounded-xl flex items-center justify-center text-2xl font-bold">F</div>
          <div>
            <h1 className="text-2xl font-extrabold tracking-tight">Fhenix — Confidential DeFi</h1>
            <p className="text-sm text-gray-300">Build private, composable on-chain apps with FHE</p>
          </div>
        </div>
        <nav className="flex items-center gap-4">
          <button onClick={() => setStep(0)} className="text-sm px-3 py-2 rounded-md hover:bg-white/5">Home</button>
          <button onClick={startQuiz} className="bg-indigo-600 px-3 py-2 rounded-md text-sm font-semibold shadow-md">Take Quiz</button>
        </nav>
      </header>

      {/* main */}
      <main className="relative z-10 w-full max-w-6xl px-6 py-12">
        {step === 0 && (
          <section className="bg-white/10 rounded-2xl p-8 backdrop-blur-md shadow-xl">
            <h2 className="text-4xl font-bold leading-tight">Confidential Computing for the Next Wave of DeFi</h2>
            <p className="mt-4 text-gray-300">Add privacy with one line of code. Encrypt trades, protect governance votes, tokenize assets without exposing holders. Testnet live — encrypt before mainnet.</p>

            <div className="mt-6 flex gap-3">
              <button onClick={startQuiz} className="bg-emerald-500 px-4 py-2 rounded-md font-semibold shadow">Start the Quiz</button>
              <button className="border border-white/10 px-4 py-2 rounded-md">Read the Docs</button>
            </div>

            <div className="mt-8 grid grid-cols-2 sm:grid-cols-3 gap-4">
              <div className="bg-white/10 p-4 rounded-lg">CoFHE — pure FHE performance</div>
              <div className="bg-white/10 p-4 rounded-lg">Redact — encrypted token wrapper</div>
              <div className="bg-white/10 p-4 rounded-lg">Hooks — MEV mitigation</div>
            </div>

            <div className="mt-8 bg-white/10 p-6 rounded-xl max-w-md">
              <h3 className="text-xl font-bold mb-2">Testnet is live</h3>
              <p className="text-sm text-gray-200">Subscribe for early access to updates, launches, and insights before mainnet.</p>
              <div className="mt-4 flex gap-2">
                <input value={email} onChange={(e) => setEmail(e.target.value)} placeholder="Email address" className="flex-1 px-3 py-2 rounded-md bg-white/5 outline-none" />
                <button className="bg-indigo-600 px-4 py-2 rounded-md font-semibold">Subscribe</button>
              </div>
            </div>
          </section>
        )}

        {step === 1 && (
          <section className="bg-white/10 rounded-2xl p-8 backdrop-blur-md shadow-xl">
            <h2 className="text-2xl font-bold mb-4">Fhenix Knowledge Quiz</h2>

            {!showResults ? (
              <>
                <div className="text-sm text-gray-300 mb-4">Question {qIndex + 1} of {QUESTIONS.length}</div>
                <h3 className="text-lg font-semibold mb-4">{QUESTIONS[qIndex].q}</h3>

                <div className="grid gap-3 mb-6">
                  {QUESTIONS[qIndex].choices.map((c, i) => (
                    <button
                      key={i}
                      onClick={() => setSelected(i)}
                      className={`text-left px-4 py-3 rounded-md border transition ${
                        selected === i
                          ? "bg-indigo-600/80 border-indigo-400"
                          : "bg-white/10 border-white/10 hover:bg-indigo-900/40"
                      }`}
                    >
                      {c}
                    </button>
                  ))}
                </div>

                <button onClick={submitAnswer} className="bg-emerald-500 px-4 py-2 rounded-md font-semibold">Submit</button>
              </>
            ) : (
              <div className="text-center">
                <h3 className="text-3xl font-bold mb-2">Your Score</h3>
                <p className="text-4xl font-extrabold text-emerald-400">{score} / {QUESTIONS.length}</p>
                <p className="text-sm text-gray-400 mt-2">Review all correct answers below 👇</p>

                <div className="mt-6 text-left bg-white/10 p-4 rounded-lg max-h-80 overflow-auto">
                  <ol className="list-decimal list-inside space-y-2 text-sm">
                    {QUESTIONS.map((qq, idx) => (
                      <li key={idx}>
                        <strong>Q{idx + 1}:</strong> {qq.choices[qq.answer]}
                        <div className="text-gray-300 text-xs mt-1">{qq.note}</div>
                      </li>
                    ))}
                  </ol>
                </div>

                <div className="mt-6 flex items-center justify-center gap-4">
                  <button onClick={restart} className="bg-indigo-600 px-4 py-2 rounded-md font-semibold">Retake Quiz</button>
                  <button onClick={() => setStep(0)} className="border px-3 py-2 rounded-md text-sm">Back to Home</button>
                </div>
              </div>
            )}
          </section>
        )}
      </main>

      {/* footer */}
      <footer className="relative z-10 w-full max-w-6xl px-6 py-8 text-gray-400 text-sm">
        <div className="flex items-center justify-between">
          <div>© {new Date().getFullYear()} Fhenix — Confidential DeFi</div>
          <div className="flex gap-4">
            <a href="#" className="underline hover:text-white">Blog</a>
            <a href="#" className="underline hover:text-white">Docs</a>
            <a href="#" className="underline hover:text-white">Ecosystem</a>
          </div>
        </div>
      </footer>

      {/* animation keyframes */}
      <style>{`
        .animate-blob { animation: blob 8s infinite; }
        .animation-delay-2000 { animation-delay: 2s; }
        .animation-delay-4000 { animation-delay: 4s; }
        @keyframes blob {
          0% { transform: translate(0px,0px) scale(1); }
          33% { transform: translate(30px,-20px) scale(1.05); }
          66% { transform: translate(-20px,30px) scale(0.95); }
          100% { transform: translate(0px,0px) scale(1); }
        }
      `}</style>
    </div>
  );
}
