import React, { useState, useEffect } from 'react';
import { MapPin, Book, History, MessageCircle, ChevronRight, ChevronLeft, CheckCircle, HelpCircle, Info, ShieldCheck, Heart, Moon, Sun, Award, Waves, ExternalLink } from 'lucide-react';

const App = () => {
  const [activeTab, setActiveTab] = useState('home');
  const [quizScore, setQuizScore] = useState(null);
  const [currentQuizIndex, setCurrentQuizIndex] = useState(0);
  const [selectedAnswers, setSelectedAnswers] = useState([]);
  const [darkMode, setDarkMode] = useState(false);

  // --- Data Sections ---
  const sections = {
    geography: {
      title: "지리적 특성",
      subtitle: "동해의 끝자락, 천혜의 섬",
      icon: <MapPin className="w-5 h-5" />,
      color: "from-blue-500 to-indigo-600",
      content: [
        { subtitle: "독도의 위치", text: "경북 울릉군 울릉읍 독도리 1~96번지. 울릉도에서 동남쪽으로 87.4km 떨어져 있어 맑은 날에는 육안으로 확인이 가능합니다." },
        { subtitle: "섬의 구성", text: "동도와 서도라는 2개의 큰 섬과 89개의 부속 도서로 이루어져 있으며, 화산 활동으로 형성된 독특한 지형을 자랑합니다." },
        { subtitle: "자연의 보호", text: "천연기념물 제336호로 지정된 독도 천연보호구역은 다양한 희귀 동식물이 서식하는 생태계의 핵심 거점입니다." },
        { subtitle: "경제적 가치", text: "주변 해역에는 풍부한 수산 자원과 함께 차세대 청정 에너지인 '메탄하이드레이트'가 대량 매장되어 있습니다." }
      ]
    },
    history: {
      title: "역사와 사료",
      subtitle: "기록이 증명하는 우리 영토",
      icon: <History className="w-5 h-5" />,
      color: "from-rose-400 to-orange-600",
      content: [
        { subtitle: "512년의 기록", text: "신라 지증왕 13년, 이사부 장군이 우산국을 복속시키며 독도는 한국 역사의 일부로 확고히 자리 잡았습니다." },
        { subtitle: "안용복의 활약", text: "조선 숙종 시기, 어부 안용복은 직접 일본으로 건너가 독도가 조선의 영토임을 명확히 확인받았습니다." },
        { subtitle: "대한제국 칙령 41호", text: "1900년 고종 황제는 법령을 통해 독도가 울도군 관할임을 선포하며 근대적 주권을 확립했습니다." },
        { subtitle: "국제법적 사실", text: "일본의 1905년 불법 편입 시도는 주권 침탈의 일환이었으며, 연합국은 전후 독도를 한국 영토로 재확인했습니다." }
      ]
    },
    peace: {
      title: "갈등과 평화",
      subtitle: "미래를 향한 지혜로운 대응",
      icon: <MessageCircle className="w-5 h-5" />,
      color: "from-emerald-400 to-teal-600",
      content: [
        { subtitle: "갈등의 원인", text: "일본의 역사 왜곡과 부당한 영유권 주장은 동아시아 평화를 위협하는 반복적인 갈등의 씨앗이 되고 있습니다." },
        { subtitle: "논리적 수호", text: "단순한 감정 표출보다는 문헌과 지도를 바탕으로 한 정확한 논리 체계를 갖추는 것이 진정한 독도 수호의 시작입니다." },
        { subtitle: "인식의 전환", text: "독도 문제를 갈등의 중심이 아닌, 동아시아의 평화적 공존을 논의하는 화해의 장으로 바라보는 시각이 필요합니다." },
        { subtitle: "우리의 역할", text: "독도에 대한 지속적인 관심과 올바른 역사 교육이 우리 영토를 지키는 가장 강력한 힘이 됩니다." }
      ]
    }
  };

  const quizData = [
    {
      question: "독도가 행정구역상 속해 있는 곳은 어디일까요?",
      options: ["경상북도 울릉군", "강원도 삼척시", "경상남도 거제시", "제주특별자치도"],
      answer: 0
    },
    {
      question: "조선 시대에 일본으로 건너가 독도가 조선 땅임을 주장한 인물은?",
      options: ["이사부", "안용복", "장보고", "최영"],
      answer: 1
    },
    {
      question: "1900년 독도를 울도군 관할로 명문화한 대한제국의 법령은?",
      options: ["칙령 제1호", "칙령 제41호", "울도군 조례", "해양영토법"],
      answer: 1
    },
    {
      question: "독도 부근 해저에 매장되어 있는 '불타는 얼음'이라 불리는 자원의 이름은?",
      options: ["천연가스", "석유", "메탄하이드레이트", "망간단괴"],
      answer: 2
    }
  ];

  const handleQuizSubmit = (optionIndex) => {
    const newAnswers = [...selectedAnswers, optionIndex];
    setSelectedAnswers(newAnswers);
    if (currentQuizIndex + 1 < quizData.length) {
      setCurrentQuizIndex(currentQuizIndex + 1);
    } else {
      let score = 0;
      newAnswers.forEach((ans, idx) => {
        if (ans === quizData[idx].answer) score++;
      });
      setQuizScore(score);
    }
  };

  const resetQuiz = () => {
    setQuizScore(null);
    setCurrentQuizIndex(0);
    setSelectedAnswers([]);
  };

  // --- Components ---
  const Header = () => (
    <header className={`sticky top-0 z-50 backdrop-blur-xl transition-all duration-500 border-b ${darkMode ? 'bg-slate-950/80 border-slate-800' : 'bg-white/80 border-slate-100'}`}>
      <div className="max-w-6xl mx-auto px-6 py-5 flex justify-between items-center">
        <div className="flex items-center gap-4 group cursor-pointer" onClick={() => setActiveTab('home')}>
          <div className="w-11 h-11 bg-gradient-to-tr from-blue-700 to-cyan-500 rounded-2xl flex items-center justify-center shadow-lg shadow-blue-500/20 transform group-hover:scale-110 transition-all duration-300">
            <ShieldCheck className="text-white w-6 h-6" />
          </div>
          <div className="leading-tight">
            <h1 className={`text-2xl font-black tracking-tight ${darkMode ? 'text-white' : 'text-slate-900'}`} style={{ fontFamily: 'system-ui, -apple-system, sans-serif' }}>독도 아카이브</h1>
            <p className="text-[10px] uppercase tracking-[0.2em] text-blue-500 font-extrabold opacity-80">Online Learning Center</p>
          </div>
        </div>
        
        <nav className={`hidden md:flex items-center p-1.5 rounded-2xl border transition-colors duration-300 ${darkMode ? 'bg-slate-900/50 border-slate-800' : 'bg-slate-100/50 border-slate-200/50'}`}>
          {[
            {id: 'home', label: '홈'},
            {id: 'learn', label: '학습'},
            {id: 'quiz', label: '퀴즈'}
          ].map(tab => (
            <button
              key={tab.id}
              onClick={() => setActiveTab(tab.id)}
              className={`px-7 py-2 rounded-xl text-[15px] font-bold transition-all duration-300 ${
                activeTab === tab.id 
                ? 'bg-white dark:bg-slate-800 text-blue-600 dark:text-white shadow-md' 
                : 'text-slate-500 hover:text-blue-500'
              }`}
            >
              {tab.label}
            </button>
          ))}
        </nav>

        <button 
          onClick={() => setDarkMode(!darkMode)}
          className={`group relative p-2.5 rounded-2xl transition-all duration-300 overflow-hidden ${darkMode ? 'bg-slate-800 text-yellow-400' : 'bg-blue-50 text-blue-600'}`}
        >
          <div className="relative z-10">
            {darkMode ? <Sun size={20} /> : <Moon size={20} />}
          </div>
          <div className={`absolute inset-0 opacity-0 group-hover:opacity-100 transition-opacity duration-300 ${darkMode ? 'bg-yellow-400/10' : 'bg-blue-600/10'}`} />
        </button>
      </div>
    </header>
  );

  const HomeView = () => (
    <div className="space-y-16 animate-in fade-in slide-in-from-top-6 duration-1000">
      <section className="relative rounded-[3rem] overflow-hidden group shadow-2xl">
        <div className={`absolute inset-0 bg-gradient-to-b ${darkMode ? 'from-slate-900/40 via-slate-950/60 to-slate-950' : 'from-blue-900/30 via-slate-900/40 to-slate-900'} z-10`} />
        <div className="h-[550px] bg-[url('https://images.unsplash.com/photo-1544652478-6653e09f18a2?auto=format&fit=crop&q=80&w=1200')] bg-cover bg-center transition-transform duration-[2000ms] group-hover:scale-110" />
        <div className="absolute inset-0 z-20 flex flex-col items-center justify-center text-center p-10">
          <div className="inline-flex items-center gap-2 px-5 py-2 rounded-full bg-white/10 backdrop-blur-xl border border-white/20 text-white text-[13px] font-bold mb-8 tracking-wide">
            <Waves size={16} className="text-cyan-300" /> 찬란한 동해의 아침을 여는 곳
          </div>
          <h2 className="text-6xl md:text-8xl font-black text-white mb-8 tracking-tighter leading-none" style={{ textShadow: '0 4px 20px rgba(0,0,0,0.3)' }}>
            <span className="opacity-90">우리 곁의</span> <br/>
            <span className="text-transparent bg-clip-text bg-gradient-to-r from-cyan-300 via-blue-400 to-indigo-400">영원한 독도</span>
          </h2>
          <p className="text-lg md:text-xl text-white/70 max-w-2xl font-medium leading-relaxed mb-10">
            천혜의 자연과 유구한 역사가 깃든 대한민국 동쪽 끝,<br/>독도가 품은 진실된 이야기를 지금 시작합니다.
          </p>
          <div className="flex flex-wrap justify-center gap-5">
            <button 
              onClick={() => setActiveTab('learn')}
              className="bg-white text-slate-950 px-10 py-5 rounded-[1.5rem] font-black text-lg hover:bg-cyan-50 transition-all transform hover:-translate-y-2 hover:shadow-xl hover:shadow-white/20 active:scale-95"
            >
              학습 시작하기
            </button>
            <button 
              onClick={() => setActiveTab('quiz')}
              className="bg-slate-950/40 backdrop-blur-xl text-white border border-white/20 px-10 py-5 rounded-[1.5rem] font-black text-lg hover:bg-slate-900 transition-all transform hover:-translate-y-2 active:scale-95"
            >
              실력 퀴즈
            </button>
          </div>
        </div>
      </section>

      <div className="grid md:grid-cols-3 gap-8">
        {Object.entries(sections).map(([key, section]) => (
          <div key={key} className={`group relative p-10 rounded-[2.5rem] border transition-all duration-500 transform hover:-translate-y-3 ${darkMode ? 'bg-slate-900/40 border-slate-800 hover:bg-slate-800 hover:border-slate-700 shadow-xl' : 'bg-white border-slate-100 hover:shadow-2xl hover:border-blue-100 shadow-sm'}`}>
            <div className={`w-16 h-16 rounded-3xl bg-gradient-to-br ${section.color} p-4 text-white shadow-lg mb-8 transform group-hover:rotate-[10deg] transition-transform duration-500`}>
              {section.icon}
            </div>
            <h3 className={`text-2xl font-black mb-3 ${darkMode ? 'text-white' : 'text-slate-800'}`}>{section.title}</h3>
            <p className={`text-[15px] mb-8 font-semibold leading-relaxed ${darkMode ? 'text-slate-500' : 'text-slate-400'}`}>{section.subtitle}</p>
            <button 
              onClick={() => setActiveTab('learn')} 
              className={`flex items-center gap-2 text-sm font-black transition-all ${darkMode ? 'text-blue-400 hover:text-blue-300' : 'text-blue-600 hover:text-blue-700'}`}
            >
              자세히 보기 <ChevronRight size={18} className="group-hover:translate-x-2 transition-transform" />
            </button>
          </div>
        ))}
      </div>
    </div>
  );

  const LearnView = () => (
    <div className="space-y-24 animate-in slide-in-from-bottom-12 duration-1000">
      {Object.entries(sections).map(([key, section]) => (
        <section key={key} className="relative">
          <div className="flex flex-col md:flex-row md:items-end justify-between gap-4 mb-12">
            <div className="flex items-center gap-5">
              <div className={`w-14 h-14 rounded-2xl bg-gradient-to-br ${section.color} flex items-center justify-center text-white shadow-xl transform -rotate-3`}>
                {section.icon}
              </div>
              <div>
                <h2 className={`text-4xl font-black tracking-tight ${darkMode ? 'text-white' : 'text-slate-900'}`}>{section.title}</h2>
                <p className="text-blue-500 font-extrabold text-[13px] uppercase tracking-widest mt-1 opacity-80">{section.subtitle}</p>
              </div>
            </div>
            <div className={`hidden md:block h-[2px] flex-1 mx-10 mb-3 opacity-20 ${darkMode ? 'bg-slate-700' : 'bg-slate-200'}`} />
          </div>
          
          <div className="grid md:grid-cols-2 gap-8">
            {section.content.map((item, idx) => (
              <div 
                key={idx} 
                className={`group p-10 rounded-[2.5rem] border transition-all duration-500 ${
                  darkMode 
                  ? 'bg-slate-900/30 border-slate-800 hover:bg-slate-900 hover:border-slate-600 shadow-md' 
                  : 'bg-white border-slate-100 shadow-sm hover:shadow-xl hover:border-blue-50'
                }`}
              >
                <div className={`w-10 h-10 rounded-xl flex items-center justify-center mb-6 transition-all duration-300 ${darkMode ? 'bg-slate-800 text-blue-400 group-hover:scale-110' : 'bg-blue-50 text-blue-600 group-hover:scale-110'}`}>
                  <CheckCircle size={22} strokeWidth={2.5} />
                </div>
                <h4 className={`text-xl font-black mb-4 tracking-tight ${darkMode ? 'text-slate-100' : 'text-slate-800'}`}>{item.subtitle}</h4>
                <p className={`text-[16px] leading-relaxed font-medium ${darkMode ? 'text-slate-400' : 'text-slate-600'}`}>{item.text}</p>
              </div>
            ))}
          </div>
        </section>
      ))}
      <div className="text-center pt-16">
        <button 
          onClick={() => setActiveTab('quiz')}
          className="group bg-slate-950 dark:bg-white text-white dark:text-slate-950 px-14 py-6 rounded-[2rem] font-black text-xl shadow-2xl hover:scale-105 transition-all inline-flex items-center gap-4"
        >
          지식 마스터 퀴즈 <ChevronRight size={26} className="group-hover:translate-x-2 transition-transform" />
        </button>
      </div>
    </div>
  );

  const QuizView = () => (
    <div className="max-w-2xl mx-auto py-10 animate-in zoom-in-95 duration-700">
      {quizScore === null ? (
        <div className={`p-12 rounded-[3rem] border shadow-[0_32px_64px_-12px_rgba(0,0,0,0.15)] transition-all duration-500 ${darkMode ? 'bg-slate-900 border-slate-800 shadow-black/50' : 'bg-white border-slate-100'}`}>
          <div className="flex justify-between items-center mb-12">
            <div className="flex items-center gap-4">
              <div className="w-12 h-12 rounded-2xl bg-indigo-500/10 flex items-center justify-center text-indigo-500">
                <HelpCircle size={24} strokeWidth={2.5} />
              </div>
              <h2 className={`text-2xl font-black tracking-tight ${darkMode ? 'text-white' : 'text-slate-800'}`}>독도 골든벨</h2>
            </div>
            <div className={`px-5 py-2 rounded-full text-[13px] font-black tracking-widest ${darkMode ? 'bg-slate-800 text-slate-400' : 'bg-slate-100 text-slate-500'}`}>
               {currentQuizIndex + 1} / {quizData.length}
            </div>
          </div>
          
          <div className="mb-12">
            <h3 className={`text-2xl md:text-3xl font-black leading-tight mb-10 tracking-tight ${darkMode ? 'text-slate-100' : 'text-slate-900'}`}>
              {quizData[currentQuizIndex].question}
            </h3>
            <div className="space-y-4">
              {quizData[currentQuizIndex].options.map((option, idx) => (
                <button
                  key={idx}
                  onClick={() => handleQuizSubmit(idx)}
                  className={`w-full text-left p-6 rounded-[1.5rem] border-2 transition-all duration-300 group flex justify-between items-center ${
                    darkMode 
                    ? 'bg-slate-800/40 border-slate-700 hover:bg-indigo-500/10 hover:border-indigo-500 text-slate-300' 
                    : 'bg-white border-slate-100 hover:bg-blue-50 hover:border-blue-500 text-slate-700'
                  }`}
                >
                  <span className="text-[17px] font-bold group-hover:text-indigo-500 dark:group-hover:text-indigo-400 transition-colors">{option}</span>
                  <div className="w-6 h-6 rounded-full border-2 border-slate-200 dark:border-slate-700 flex items-center justify-center group-hover:border-indigo-500 transition-all">
                    <div className="w-2.5 h-2.5 rounded-full bg-indigo-500 scale-0 group-hover:scale-100 transition-transform" />
                  </div>
                </button>
              ))}
            </div>
          </div>
          
          <div className="relative w-full h-4 bg-slate-100 dark:bg-slate-800 rounded-full overflow-hidden">
            <div 
              className="absolute left-0 top-0 h-full bg-gradient-to-r from-blue-600 via-indigo-500 to-cyan-400 transition-all duration-1000 ease-out rounded-full shadow-[0_0_15px_rgba(79,70,229,0.5)]" 
              style={{ width: `${((currentQuizIndex) / quizData.length) * 100}%` }}
            />
          </div>
        </div>
      ) : (
        <div className={`p-16 rounded-[4rem] border shadow-2xl text-center transition-all duration-500 ${darkMode ? 'bg-slate-900 border-slate-800 text-white' : 'bg-white border-slate-100'}`}>
          <div className={`inline-flex items-center justify-center w-32 h-32 rounded-[2.5rem] mb-10 transform rotate-6 shadow-2xl ${quizScore === quizData.length ? 'bg-yellow-400 text-slate-900' : 'bg-blue-600 text-white'}`}>
            <Award size={64} strokeWidth={1.5} />
          </div>
          <h2 className="text-5xl font-black mb-4 tracking-tighter italic uppercase">Mission Clear</h2>
          <p className={`mb-12 text-xl font-bold ${darkMode ? 'text-slate-400' : 'text-slate-500'}`}>
            당신의 독도 사랑 지수는 <span className="text-indigo-500 font-black text-4xl block mt-2 tracking-normal">{quizScore} / {quizData.length}</span>
          </p>
          <div className="flex flex-wrap gap-4 justify-center">
            <button 
              onClick={resetQuiz}
              className={`px-10 py-5 rounded-2xl font-black text-lg transition-all ${darkMode ? 'bg-slate-800 text-slate-300 hover:bg-slate-700' : 'bg-slate-100 text-slate-700 hover:bg-slate-200'}`}
            >
              재도전
            </button>
            <button 
              onClick={() => setActiveTab('home')}
              className="px-10 py-5 rounded-2xl font-black text-lg bg-indigo-600 text-white hover:bg-indigo-700 transition-all shadow-xl shadow-indigo-500/30"
            >
              메인 화면으로
            </button>
          </div>
          {quizScore === quizData.length && (
            <div className={`mt-12 p-8 rounded-[2rem] border-2 border-dashed flex flex-col items-center gap-4 animate-pulse ${darkMode ? 'bg-indigo-900/20 border-indigo-500/30 text-indigo-400' : 'bg-blue-50 border-blue-200 text-blue-800'}`}>
              <Heart className="fill-current" size={40} />
              <p className="font-black text-lg">독도의 미래를 지키는 자랑스러운 수호자입니다!</p>
            </div>
          )}
        </div>
      )}
    </div>
  );

  return (
    <div className={`min-h-screen font-sans transition-all duration-700 pb-32 selection:bg-indigo-500 selection:text-white ${darkMode ? 'bg-slate-950 text-slate-200' : 'bg-[#fcfdfe] text-slate-900'}`} style={{ fontFamily: '"Pretendard", "Inter", -apple-system, sans-serif' }}>
      <Header />
      
      <main className="max-w-6xl mx-auto px-6 py-16">
        {activeTab === 'home' && <HomeView />}
        {activeTab === 'learn' && <LearnView />}
        {activeTab === 'quiz' && <QuizView />}
      </main>

      <footer className={`max-w-6xl mx-auto px-10 pt-20 border-t transition-all duration-700 ${darkMode ? 'border-slate-900 text-slate-700' : 'border-slate-100 text-slate-400'}`}>
        <div className="flex flex-col md:flex-row justify-between items-start md:items-center gap-10 mb-12">
          <div className="space-y-4">
            <div className="flex items-center gap-3 opacity-60">
              <ShieldCheck size={24} className="text-blue-500" />
              <span className="font-black text-lg uppercase tracking-tighter">Dokdo Archive</span>
            </div>
            <p className="text-xs font-bold leading-loose max-w-sm opacity-50 uppercase tracking-widest">
              지정학적 요충지이자 생태계의 보고,<br/>독도는 영원한 대한민국 영토입니다.
            </p>
          </div>
          <div className="grid grid-cols-2 gap-x-16 gap-y-4 text-sm font-black uppercase tracking-[0.15em]">
            <button onClick={() => setActiveTab('home')} className="hover:text-indigo-500 transition-colors text-left">Main</button>
            <button onClick={() => setActiveTab('learn')} className="hover:text-indigo-500 transition-colors text-left">Archive</button>
            <button onClick={() => setActiveTab('quiz')} className="hover:text-indigo-500 transition-colors text-left">Challenge</button>
            <a href="#" className="flex items-center gap-2 hover:text-indigo-500 transition-colors">Support <ExternalLink size={12} /></a>
          </div>
        </div>
        <div className="flex flex-col md:flex-row justify-between items-center gap-4 py-8 border-t border-slate-100/5 dark:border-slate-900/50">
          <p className="text-[10px] font-bold opacity-40 uppercase tracking-widest">© 2024 DOKDO DIGITAL ARCHIVE PROJECT. NO RIGHTS RESERVED FOR PUBLIC GOOD.</p>
          <div className="flex gap-6 opacity-30">
            <Info size={16} />
            <Award size={16} />
            <Book size={16} />
          </div>
        </div>
      </footer>
    </div>
  );
};

export default App;
