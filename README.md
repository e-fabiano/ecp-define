# ecp-define
Driver to set turbomole input with basis sets from the pseudopotential library (https://pseudopotentiallibrary.org/)

USAGE:
Provide a coord file (coordinate file in TURBOMOLE format) then run
ecp-define [options]

OPTIONS:
  -b or --basis <string>    name of the basis set to be used (default: aug-cc-pVDZ)
  -s                        use symmetry (default: do not use)
  -f or --freeze \"<string>\" use <string> to set the frozen atoms (default: no freeze)
  -c or --charge <number>   total charge of the system (default: 0)
  --no-ri                   turn off RI approximation (default: on)
  --ri-mem <number>         set memory for RI (default: 5000)
  -cc <string>              set correlated calculations: mp2, cc2, mp3, mp4, ccsd(t)
                            (default: do not set)
  --turbodir                set TURBODIR (default: from system value)
  --bse-exec                bse executable [from https://molssi-bse.github.io/basis_set_exchange/] 
                            (default: which bse)
  -v or --verbose           print additional output
  -h or --help              print this help
  
