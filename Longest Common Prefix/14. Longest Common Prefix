/**
 * @param {string[]} strs
 * @return {string}
 */

 var longestCommonPrefix = function(strs) {
    if (strs.length === 0) return "";
    strs.sort();
    let str = "";
    let first = strs[0];
    let last = strs[strs.length - 1];

    for (let i = 0; i < first.length; i++) {
        if (first[i] !== last[i]) {
            break;
        }
        str += first[i];
    }

    return str;
};
