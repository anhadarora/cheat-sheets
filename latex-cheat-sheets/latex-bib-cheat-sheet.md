# LaTeX Bib Cheat Sheet

## Official Documents

- [How to Use the IEEEtran BIBTEX Style](ftp://ftp.dante.de/tex-archive/biblio/bibtex/contrib/IEEEtran/IEEEtran_bst_HOWTO.pdf)
- [IEEE Citation Reference](http://www.ieee.org/documents/ieeecitationref.pdf)
- [Citing and referencing: Standard abbreviations used in the IEEE Reference list](http://guides.lib.monash.edu/c.php?g=219786&p=1454302)

## Abbreviations

Where to find the abbreviations of journals:
- The journal option of [MathSciNet](http://www.ams.org/mathscinet/index.html)
- [Wikipedia; take TOCS for an example](https://en.wikipedia.org/wiki/ACM_Transactions_on_Computer_Systems)

Where to find the abbreviations of conferences:

### Journals

- [JACM] `J. ACM`  =  `Journal of the ACM `
- [DC] `Distrib. Comput.`  =  `Distributed Computing`
- [TPDS] `{IEEE} Trans. Parallel Distrib. Syst.`  =  `{IEEE} Transactions on Parallel and Distributed Systems`
- [TOPLAS] `ACM Trans. Program. Lang. Syst.`  =  `ACM Transactions on Programming Languages and Systems`
- [IPL] `Inform. Process. Lett.`  =  `Information Processing Letters`
- [TOCS] `ACM Trans. Comp. Syst.`  =  `ACM Transactions on Computer Systems`
- [VLDB] `Proc. VLDB Endow.`  =  `Proceedings of the VLDB Endowment`

### [Conferences](http://www.ieee.org/documents/ieeecitationref.pdf)

#### Abbrev
- `Annals`  =>  `Ann.`
- `Annual`  => `Annu.`
- `International`  =>  `Int.`
- `Proceedings` => `Proc.`
- `Conference`  =>  `Conf.`
- `Symposium` => `Symp.`
- `Colloquium`  =>  `Colloq.`
- `Congress`  =>  `Congr.`
- `First | Second | Third`  =>  `1st | 2nd | 3rd`

#### Omit
- `of the`
- `on`

#### Abbrev again
- `System(s)`  =>  `Syst.`
- `Distributed` => `Distrib.`
- `Computing` => `Comput.`
- `Computer(s)` => `Comput.`

## Authors
- [Using `et al` when the author list is too long](http://tex.stackexchange.com/a/164513/23098)
```
%%%%% in `.bib` file:
@IEEEtranBSTCTL{IEEEexample:BSTcontrol,
  CTLuse_forced_etal       = "yes",
  CTLmax_names_forced_etal = "3",
  CTLnames_show_etal       = "2" 
}
%%%%% in `.txt` file:
\begin{document}
\bstctlcite{IEEEexample:BSTcontrol}
```
