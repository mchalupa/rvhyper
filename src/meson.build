
sources = [
  'CachedTrace.cpp',
  'MonitorAutomaton.cpp',
  'Trie.cpp',
  'Event.cpp',
  'MonitorAutomatonTemplate.cpp',
  'VectorTrace.cpp',
  'FileTrace.cpp',
  'Monitoring.cpp',
  'diagnostic.cpp',
  'Formula.cpp',
  'NoLiveMonitoring.cpp',
  'flags.cpp',
  'GeneralSelectionHelper.cpp',
  'Parser.cpp',
  'getopt.cpp',
  'Lexer.cpp',
  'RememberingSelectionHelper.cpp',
  'LexerUtil.cpp',
  'SelectionHelper.cpp',
  'timer.cpp',
  'LiveMonitoring.cpp',
  'Token.cpp',
  'LiveTrace.cpp',
  'Trace.cpp'
]

rvhyper_lib = static_library(
  'rvhyper',
  sources: sources,
  install: true,
  dependencies: [spot_dep]
)

exe = executable(
  'rvhyper',
  'main.cpp',
  link_with: [rvhyper_lib],
  dependencies: [spot_dep],
  install : true,
)

