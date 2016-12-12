## Mathematica Software for the Numerical Generation of Given Distribution with Exponential Autocorrelation Function

This directory includes Mathematica files for generation of samples of a random processes with a given probability density function (PDF) and  with an exponential autocorrelation function (ACF). These files also provide a statistical validation of the resulting processes.

The following files are included:
- `ProcessWithExpACF.nb` and `ProcessWithExpACF.m`: Mathematica module for random process generation.
- `Chi-Square.nb`, `HalfNormal_Dist.nb`, `Laplase_Dist.nb`: The generation module is applied for χ2, half-normal and Laplase distributions.
- `Laplase_Dist_nomod.nb`: The process generation is performed inside the same file without module applied.

Note: The length of generated sequence influences the validation results. For the best visual results the number of samples, **length**>= 5*10^6. The main drawback is that takes time...

[comment]: # (supplementary downloadable material, provided by the authors of the paper:)
[comment]: # (D. Bykhovsky and V. Lyandres, "**On the Numerical Generation of Positive-Axis-Defined Distributions with Exponential Autocorrelation Function**")

This source code was created and verified at version 11 of Mathematica.

THIS SOFTWARE IS PROVIDED BY AUTHORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.