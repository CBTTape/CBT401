# CBT401
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)
This is still a work in progress. GitHub repos will be deleted and created during this period...
~~~~~~~~~~~~~~~~

//***FILE 401 is from Bob Goldberg and contains SPITBOL 360, the    *   FILE 401
//*           earlier implementation of SPITBOL, which is a         *   FILE 401
//*           compiler version of SNOBOL 4.                         *   FILE 401
//*                                                                 *   FILE 401
//*           email:  "Bob Goldberg" <gman_bob@yahoo.com>           *   FILE 401
//*                   "Bob Goldberg" <gman_bob@pacbell.net>         *   FILE 401
//*                                                                 *   FILE 401
//*      SPITBOL 360 $README FILE                                   *   FILE 401
//*      ------------------------                                   *   FILE 401
//*                                                                 *   FILE 401
//*      11/08/2001  Updated for Hercules AWS installation          *   FILE 401
//*                  (Bob Goldberg)                                 *   FILE 401
//*       8/20/2001  Initial Version (Bob Goldberg)                 *   FILE 401
//*                                                                 *   FILE 401
//*      Readme Contents                                            *   FILE 401
//*      ---------------                                            *   FILE 401
//*                                                                 *   FILE 401
//*      What is SPITBOL 360?                                       *   FILE 401
//*                                                                 *   FILE 401
//*      Installation Overview                                      *   FILE 401
//*                                                                 *   FILE 401
//*      General Installation                                       *   FILE 401
//*                                                                 *   FILE 401
//*      Hercules AWS Intallation                                   *   FILE 401
//*                                                                 *   FILE 401
//*      Reassembling the Compiler                                  *   FILE 401
//*                                                                 *   FILE 401
//*      Acknowledgments                                            *   FILE 401
//*                                                                 *   FILE 401
//*      What is SPITBOL 360? [*]                                   *   FILE 401
//*      ------------------------                                   *   FILE 401
//*                                                                 *   FILE 401
//*      SPITBOL 360 is an implementation of the SNOBOL4            *   FILE 401
//*      programming language for use on IBM 360 compatible         *   FILE 401
//*      computers. SPITBOL is considerably smaller than the        *   FILE 401
//*      original implementation of SNOBOL4 and has execution       *   FILE 401
//*      speeds up to ten times faster. For certain programs,       *   FILE 401
//*      notably those with in-line patterns, the gain in speed     *   FILE 401
//*      may be even greater.                                       *   FILE 401
//*                                                                 *   FILE 401
//*      Unlike SIL SNOBOL4[**], which is an interpreter,           *   FILE 401
//*      SPITBOL is a true compiler which generates executable      *   FILE 401
//*      machine code. Of course, the complexity of the SNOBOL4     *   FILE 401
//*      language dictates that system subroutines be used for      *   FILE 401
//*      many common functions.                                     *   FILE 401
//*                                                                 *   FILE 401
//*      SPITBOL can be run as an 'in-core' 'load-and-go' system    *   FILE 401
//*      like WATFIV, where programs are executed as soon as they   *   FILE 401
//*      are compiled.  Alternately, the compiler can generate      *   FILE 401
//*      object modules that can be linked with a run-time          *   FILE 401
//*      library to create load modules for later execution.        *   FILE 401
//*                                                                 *   FILE 401
//*      SPITBOL 360 was originally distributed under license,      *   FILE 401
//*      for a fee.[***] Effective November, 2001, SPITBOL 360      *   FILE 401
//*      will be distributed under the General Public License       *   FILE 401
//*      (GPL), for no fee.                                         *   FILE 401
//*                                                                 *   FILE 401
//*      To obtain current information and distribution files       *   FILE 401
//*      for SPITBOL 360, visit:                                    *   FILE 401
//*                                                                 *   FILE 401
//*          http://www.snobol4.com                                 *   FILE 401
//*                                                                 *   FILE 401
//*      ----                                                       *   FILE 401
//*                                                                 *   FILE 401
//*      [*] SPITBOL = SPeedy ImplemenTation of SNOBOL4             *   FILE 401
//*                    --     -       -            ---              *   FILE 401
//*                                                                 *   FILE 401
//*      [**] The original SNOBOL4 implementation from Bell         *   FILE 401
//*      Telephone Laboratories was developed by R. E. Griswold     *   FILE 401
//*      and I. Polonsky, the designers of the SNOBOL4              *   FILE 401
//*      programming language. Thus, this reference                 *   FILE 401
//*      implementation is often referred to as BTL SNOBOL4. In     *   FILE 401
//*      the early 1970s, after Griswold left BTL for The           *   FILE 401
//*      University of Arizona and continued SNOBOL4 distribution   *   FILE 401
//*      from there, this implementation gained another name: SIL   *   FILE 401
//*      SNOBOL4. (SIL = SNOBOL4 Implementation Language)           *   FILE 401
//*                                                                 *   FILE 401
//*      [***] SPITBOL 360 was distributed from 1971 until 1984     *   FILE 401
//*      when it was superseded by SPITBOL 370.                     *   FILE 401
//*                                                                 *   FILE 401
~~~~~~~~~~~~~~~~

